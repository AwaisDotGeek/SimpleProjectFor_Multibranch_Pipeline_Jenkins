pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // Define your build steps here
                echo 'Building...'
                // Add more build steps as needed
            }
        }
        stage('Test') {
            steps {
                // Define your test steps here
                echo 'Testing...'
                // Add more test steps as needed
            }
        }
        stage('Deploy') {
            steps {
                // Define your deployment steps here
                echo 'Deploying...'
                // Add more deployment steps as needed
            }
        }
    }
    
    post {
        always {
            // Clean up or perform any post-build actions here
            echo "Done!"
        }
    }
}
