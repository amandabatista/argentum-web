pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
                sh 'make clean'
            }
        }
        stage('Test'){
            steps {
                sh 'make test'
            }
        }
        stage('Deploy') {
            steps {
                sh 'make publish'
            }
        }
    }
}
