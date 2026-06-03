pipeline {
    agent any

    tools {
        nodejs 'node18'
    }

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Show Files') {
            steps {
                sh 'ls -la'
            }
        }

        stage('Node Check') {
            steps {
                sh 'node -v'
                sh 'npm -v'
            }
        }

        stage('Docker Check') {
            steps {
                sh 'docker --version'
            }
        }
    }
}