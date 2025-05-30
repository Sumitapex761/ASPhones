pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/aman-3701/ASPhones.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add build steps here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // Add deployment steps here
            }
        }
    }
}
