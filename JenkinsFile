pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo "Checking out from python branch"
            }
        }
        stage('Run Python') {
            steps {
                sh 'python3 hello.py'
            }
        }
    }
}