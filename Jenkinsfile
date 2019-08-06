pipeline {
    agent {
        docker { image 'node:7-alpine'}
    }
    stages {
        stage('TEST') {
            steps {
                sh 'node --version'
            }
        }
    }
}