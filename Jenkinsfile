pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                echo 'Cloning repository...'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t project4-cicd:v1 .'
            }
        }

        stage('Run Docker Container') {
            steps {
                sh 'docker rm -f project4 || true'
                sh 'docker run -d --name project4 -p 8085:80 project4-cicd:v1'
            }
        }
    }
}
