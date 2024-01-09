pipeline {
    agent any  // Specifies that the pipeline can run on any available agent (Jenkins slave).

    stages {
        stage('Checkout') {
            steps {
                // Checkout the source code from your version control system (e.g., Git).
                script {
                    checkout scm
                }
            }
        }

        stage('Build') {
            steps {
                // Perform the build steps (e.g., compile code).
                script {
                    echo 'Building...'
                    // Add your build commands here.
                }
            }
        }

        stage('Test') {
            steps {
                // Run tests.
                script {
                    echo 'Testing...'
                    // Add your test commands here.
                }
            }
        }

        stage('Deploy') {
            steps {
                // Deploy the application (e.g., to a staging or production environment).
                script {
                    echo 'Deploying...'
                    // Add your deployment commands here.
                }
            }
        }
    }
}
