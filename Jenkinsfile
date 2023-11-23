pipeline {
    agent any
    stages {
        stage("Build") {
            steps {
                sh '''
                '''
            }
        }
        stage("Push") {
            steps {
                sh '''
                '''
            }
        }
        stage("Deploy") {
            steps {
                sh '''
                kubectl apply -f .
                sleep 60
                kubectl get services
                '''
            }
        }
    }
}