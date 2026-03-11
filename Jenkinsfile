pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Installing dependencies'
                bat 'npm install'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application'
                bat 'npm start'
            }
        }
    }
}
