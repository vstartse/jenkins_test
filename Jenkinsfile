pipeline {
    agent any
    stages {
        stage('build'){
            agent {
                docker {image 'vladstarcev/jenkins-exercise'}
            }
            steps {
                sh 'python3 main.py'
            }
        }
        stage('Test'){
            agent {
                docker {image 'node:16.13.1-alpine'}
            }
            steps {
                sh 'node --version'
            }
        }
    }
}