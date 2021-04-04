pipeline {
    agent {
        label 'docker'
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}