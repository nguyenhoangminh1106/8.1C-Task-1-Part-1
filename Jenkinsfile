pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                sh 'echo "Build step (e.g., mvn package)"'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running unit and integration tests...'
                sh 'echo "Test step (e.g., mvn test)"'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Performing code analysis...'
                sh 'echo "Code analysis step (e.g., SonarQube)"'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Running security scan...'
                sh 'echo "Security scan step (e.g., OWASP Dependency-Check)"'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to staging...'
                sh 'echo "Staging deployment step (e.g., AWS EC2)"'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests on staging...'
                sh 'echo "Staging tests step (e.g., Postman, Newman)"'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying to production...'
                sh 'echo "Production deployment step (e.g., AWS EC2)"'
            }
        }
    }
}
