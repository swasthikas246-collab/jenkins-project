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
                sh 'ls -l'
            }
        }

        stage('Remove test.txt') {
            steps {
                sh 'rm -f test.txt'
            }
        }

        stage('Check Files') {
            steps {
                sh 'ls -l'
            }
        }
    }
}
