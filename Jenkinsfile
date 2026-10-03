pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                sh 'docker build -t aditipatel18/my-first-app:jenkins .'
            }
        }

        stage('Test Docker Image') {
            steps {
                sh 'docker images aditipatel18/my-first-app'
            }
        }
    }
}
