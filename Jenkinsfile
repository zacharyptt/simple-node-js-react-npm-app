pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
        stage('Deliver') { 
            steps {
                sh './jenkins/scripts/deliver.sh'
            }
        }
    }
}