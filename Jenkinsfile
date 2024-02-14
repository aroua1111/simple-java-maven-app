pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'mvn --version'
                sh 'node --version'
                sh 'ruby --version'
                sh 'python --version'
                sh 'php --version'
                sh 'go --version'
            }
        }
    }
}

