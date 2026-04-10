pipeline {
    agent any

    stages {
        stage('Show Files') {
            steps {
                sh 'pwd'
                sh 'ls -la'
            }
        }

        stage('Check Python') {
            steps {
                sh 'python3 --version'
            }
        }

        stage('Run App') {
            steps {
                sh 'python3 main.py'
            }
        }
    }
}
