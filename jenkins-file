pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo "Cloning from GitHub..."
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo 'Running build process...'
                // Example: sh 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
    }
}
