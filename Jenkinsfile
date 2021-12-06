pipeline {
    agent any 
    stages {
        stage("DEV_DEPLOY") {
            steps {
                echo "DEV_DEPLOY the application..."
            }
        }
        stage("QA_DEPLOY") {
            steps {
                echo "QA_DEPLOY the application..." 
            }
        }
        stage("CLEANUP") {
            steps {
                echo "CLEANUP the application..."
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
