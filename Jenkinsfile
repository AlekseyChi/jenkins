pipeline {
    agent any

    stages {
        stage('Flask-project') {
            steps {
                sh 'COMPOSE_HTTP_TIMEOUT=200 docker-compose up -d'
            }
        }
    }
}
