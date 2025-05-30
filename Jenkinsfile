pipeline {
    agent any

    tools {
        jdk 'jdk-17'      // Change name to match your Jenkins JDK installation
        maven 'maven-3.8' // Change name to match your Jenkins Maven installation
    }

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/aman-3701/ASPhones.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment step goes here (manual or SSH or copying JAR)'
            }
        }
    }
}
