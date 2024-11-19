pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Rohan040201/repo.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building the project..."'
            }
        }
    }
}
