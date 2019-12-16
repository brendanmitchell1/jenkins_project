pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'Javac Student'
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