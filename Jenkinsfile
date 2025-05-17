pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                bat 'echo "Build step (e.g., mvn package)"'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running unit and integration tests...'
                bat 'echo "Test step (e.g., mvn test)"'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Performing code analysis...'
                bat 'echo "Code analysis step (e.g., SonarQube)"'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Running security scan...'
                bat 'echo "Security scan step (e.g., OWASP Dependency-Check)"'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to staging...'
                bat 'echo "Staging deployment step (e.g., AWS EC2)"'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests on staging...'
                bat 'echo "Staging tests step (e.g., Postman, Newman)"'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying to production...'
                bat 'echo "Production deployment step (e.g., AWS EC2)"'
            }
        }
    }
}
