pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'TaskFlow GitHub Repository Connected'
            }
        }

        stage('Build') {
            steps {
                echo 'Building TaskFlow Application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running Application Tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment Stage Started'
            }
        }
    }
}
