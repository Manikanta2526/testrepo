pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                sh "git status"
            }
        }
        stage('Test') {
            steps {
                echo 'Running unit tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to server...'
            }
        }
    }
}
