pipeline {
    agent any
    environment {
        testvariable = "custom variable"
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo "This is build stage"'
                sh "echo this is test --> ${testvariable}"
            }
        }
        stage('Test') {
            steps {
                sh 'echo "This is test stage"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "This is deploy stage one"'
            }
        }
    }
}
