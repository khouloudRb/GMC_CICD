pipeline {
    agent none
    stages {
        stage('Back-end') {
            agent {
                docker { image 'khouloud123456/backend:1' }
            }
            steps {
                echo 'build backend1'
            }
        }
        stage('Front-end') {
            agent {
                docker { image 'khouloud123456/frontend:2' }
            }
            steps {
                echo 'build frontend'
            }
        }
    }
}
