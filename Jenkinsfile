pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                // Here you could add build steps if needed, like compiling code
            }
        }
        
        stage('Test') {
            steps {
                echo 'Testing the application...'
                // Here you could add test steps if needed
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Here you could add deployment steps if needed
                // For a simple Hello World app, deployment might involve copying files to a server
                sh 'sudo cp index.html /home/ec2-user/vasanth'
            }
        }
    }
}
