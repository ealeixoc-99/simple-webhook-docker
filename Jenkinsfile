pipeline {
    agent any

    stages {
        stage('Docker Build') {
            steps {
                bat 'docker compose up'
            }
        }
    }
}
