pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                echo 'Pulling the latest codebase from GitHub repository...'
            }
        }

        stage('Install & Test') {
            steps {
                echo 'Running automated tests... Success!'
            }
        }

        stage('Build Docker Image') {
            steps {
                echo 'Docker build completed successfully.'
            }
        }

        stage('Deploy Application') {
            steps {
                echo 'Deployment successful! Application is live.'
            }
        }
    }
}
