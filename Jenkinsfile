pipeline {
    agent { docker { image 'python:3.9.0'  args '-p 3000:3000' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'pytest tests'
            }
        }
    }
}