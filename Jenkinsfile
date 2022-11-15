pipeline {
    agent {
        docker {image 'node:16.13.1-alpine'}
    }

    environment{
        NAME = 'Vlad'
    }

    stages {
        stage('Test'){
            steps {
                sh 'node --version'
            }
        }
    }
}