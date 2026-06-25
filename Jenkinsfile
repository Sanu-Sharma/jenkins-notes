pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Code checkout'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the app...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing the app...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the app...'
            }
        }
    }
    post {
        success { echo 'Pipeline successful!' }
        failure { echo 'Pipeline failed!' }
    }
}
