pipeline {
    agent {
        docker {
            image 'node:6-alpine'
            args '-p 4040:4040'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}