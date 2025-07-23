pipeline {
    agent any
    stages {
        stage('checkout code') {
            steps {
                git branch: 'main', url: 'https://github.com/shrimal2004/Test1.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "building the app"'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running the tests"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "deploying"'
            }
        }
    }
}
