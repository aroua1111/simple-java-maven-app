pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'mvn --version'
                sh 'echo Hello world'
                sh '''
                 echo "Multiples"
                 ls -ltr
                  '''
            }
        }
    }
}

