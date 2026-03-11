pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Installing dependencies'
                sh 'npm install'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application'
                sh 'npm start'
            }
        }
    }
}
