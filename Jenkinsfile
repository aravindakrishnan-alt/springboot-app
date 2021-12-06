pipeline {
    agent any 
    stages {
        stage("Build") {
            steps {
                echo "Building the application..."
            }
        }
        stage("Test") {
            steps {
                echo "Testing the application..." 
            }
        }
        stage("Deploy") {
            steps {
                echo "Deploying the application..."
            }
        }       
    }

    post {
        always {
            echo "always it executes"
        }
        success {
            echo "when success it executes"
        }
        failure {
            echo "when failure it executes"
        }
        unstable {
            echo "when unstable it executes"
        }
    }

}
