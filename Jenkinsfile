pipeline {
    agent any
    
    stages {
        stage('Build and Test') {
            steps {
                // Checkout the code from the repository
                checkout scm
                
                // Perform build and test steps
                sh 'ls -la' // List files in the workspace directory (for demonstration)
                // Add more build and test commands here as needed
            }
        }
    }
    
    // Post-build actions (optional)
    post {
        always {
            // Clean up or perform any post-build actions here
        }
    }
}
