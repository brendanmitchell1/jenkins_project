pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat "javac Student.java"
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