pipeline {
    agent { any }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'pytest tests'
            }
        }
    }
}