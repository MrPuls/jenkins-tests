Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'python:3.9.0' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'pytest'
            }
        }
    }
}