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
                // Copy the file from GitHub to the Jenkins workspace
                sh 'wget -O index.html https://github.com/saiteja3312/DemoGit.git'
                
                // Now you can manipulate the file in the workspace directory
                // For example, you can copy it to another location
                sh 'cp index.html /root'
            }
        }
    }
}
