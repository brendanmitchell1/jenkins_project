pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat "javac Student"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}