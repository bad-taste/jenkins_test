pipeline {
    agent any
    
    environment {
        PROJECT_NAME = "Neptun"
        OWNER_NAME = "Romko Bomko"
    }

    stages {
        stage('1-Build') {
            steps {
                echo "Start of Stage Build"
                echo "Building......."
                echo "End of Stage Build"
            }
        }
        stage('2-Test') {
            steps {
                echo "Start of Stage Test"
                echo "Testing......."
                sh "ls -la"
                echo "Hello ${OWNER_NAME}"
                echo "Project ${PROJECT_NAME}"
                echo "End of Stage Build"
            }
        }
        stage('3-Deploy') {
            steps {
                echo "Start of Stage Deploy"
                echo "Deploying......."
                echo "End of Stage Build"
            }
        }
        stage('4-Celebrate') {
            steps {
                echo "Start of Stage Deploy"
                echo "Good Job!"
                echo "End of Stage Build"
            }
        }
    }
}