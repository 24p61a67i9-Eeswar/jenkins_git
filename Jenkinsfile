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
                bat '"C:\\Users\\NALANDA\\AppData\\Local\\Programs\\Python\\Python312\\python.exe" main.py'
            }
        }

    }
}
