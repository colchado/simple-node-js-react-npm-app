pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3013:3013' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
