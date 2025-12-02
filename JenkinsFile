pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo "Checking out from main branch (Java)"
            }
        }
        stage('Compile Java') {
            steps {
                sh 'javac HelloWorld.java'
            }
        }
        stage('Run Java') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}