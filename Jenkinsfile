pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('List Files') {
            steps {
                bat 'dir'
            }
        }

        stage('Remove test.txt') {
            steps {
                bat 'del test.txt'
            }
        }

        stage('Check Files') {
            steps {
                bat 'dir'
            }
        }
    }
}
