pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building the code'
                echo 'Tool: Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running unit and integration tests'
                echo 'Tools: JUnit, Jest'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Performing code analysis'
                echo 'Tool: SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo ' Performing security scan to identify vulnerabilities'
                echo 'Tool: Snyk'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to staging server'
                echo 'Tool: AWS CLI'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests on staging'
                echo 'Tools: Postman, Selenium'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying to production server'
                echo 'Tools: AWS CLI, Docker'
            }
        }

        stage('Testing Commit Changes') {
            steps {
                echo 'Testing.'
            }
        }
    }
}
