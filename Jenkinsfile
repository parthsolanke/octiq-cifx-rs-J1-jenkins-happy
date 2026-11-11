pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'cargo build --all-targets'
            }
        }
        stage('Test') {
            steps {
                sh 'cargo test'
            }
        }
    }
}
