pipeline {
    agent any

    stages {
        stage('Frontend Build') {
            steps {
                echo 'Building Frontend Application'
                bat 'cd frontend && echo "Frontend build completed"'
            }
        }

        stage('Backend Build') {
            steps {
                echo 'Building Backend Application'
                bat 'cd backend && echo "Backend build completed"'
            }
        }

        stage('Test') {
            steps {
                echo 'Running application tests'
            }
        }

        stage('Deployment') {
            steps {
                echo 'Deploying application'
            }
        }

        stage('Verification') {
            steps {
                echo 'Verifying application deployment'
            }
        }
    }
}
