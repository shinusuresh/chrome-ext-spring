pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            checkout scm
            steps {
                sh 'java --version'
            }
        }
    }
}
