pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                // Example command to build (replace with your actual build command)
                sh 'echo "Building..."'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Example test command (replace with your actual test command)
                sh 'echo "Running tests..."'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Example deploy command (replace with your actual deploy command)
                sh 'echo "Deploying..."'
            }
        }
    }
    post {
        success {
            echo 'Build Successful!!!!!!!!!!!!!!!!'
        }
        failure {
            echo 'Build Failed. Please check the logs.'
        }
    }
}

