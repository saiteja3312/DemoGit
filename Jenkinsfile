pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'javac HelloWorld.java'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add commands to run tests here. For simplicity, we're just echoing.
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add deployment commands here. For simplicity, we're just echoing.
            }
        }
    }
}
