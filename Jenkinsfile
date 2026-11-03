pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Repository downloaded successfully.'
            }
        }

        stage('Build') {
            steps {
                bat 'echo Building Project...'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Testing Project...'
            }
        }

        stage('Success') {
            steps {
                bat 'echo CI/CD Pipeline Executed Successfully.'
            }
        }
    }
}
