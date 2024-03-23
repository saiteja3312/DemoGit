pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Here you could add build steps if needed, like compiling code
            }
        }
        stage('Test') {
            steps {
                // Here you could add test steps if needed
            }
        }
        stage('Deploy') {
            steps {
                // Here you could add deployment steps if needed
                // For a simple Hello World app, deployment might involve copying files to a server
                sh cp index.html /home/ec2-user/vasanth
            }
        }
    }
}
