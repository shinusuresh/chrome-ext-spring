pipeline {
    checkout scm
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'java --version'
            }
        }
    }
}
