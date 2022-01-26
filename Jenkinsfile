pipeline {
    agent any

    triggers {
        githubPush()
    }
    
    stages {
        stage('Docker Build') {
            steps {
                bat 'docker compose up'
            }
        }
    }
}
