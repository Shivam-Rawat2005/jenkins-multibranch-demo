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
                echo 'Building project on branch: main'
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