pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code checkout completed'
            }
        }

        stage('Build') {
            steps {
                echo 'This is development branch pipeline'
            }
        }

        stage('Test') {
            steps {
                echo 'Running test cases'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application'
            }
        }
    }
}