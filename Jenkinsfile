pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'flask --help'
                sh 'python --version'
            }
        }
    }
}
