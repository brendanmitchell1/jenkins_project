pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                'javac Student'
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