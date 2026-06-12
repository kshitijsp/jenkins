pipeline {
    agent {label 'slave'}
    // agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building.................'
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
