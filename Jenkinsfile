pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Saksh-says/HelloWorld.git'
            }
        }

        stage('Compile') {
            steps {
                sh 'javac HelloWorld.java'
            }
        }

        stage('Execute') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}

