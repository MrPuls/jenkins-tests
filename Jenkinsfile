pipeline {
    agent {
        docker {
            image 'python 3.9.0'
            args '-p 8080:8080'
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'pytest tests'
            }
        }
    }
}