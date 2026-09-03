pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checkout completed'
            }
        }

        stage('Build') {
            steps {
                bat 'python main.py'
            }
        }

    }
}
