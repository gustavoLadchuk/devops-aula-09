pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                docker compose up -d --build
		docker ps
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
