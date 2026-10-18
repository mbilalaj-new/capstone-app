pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo Build OK'
            }
        }
        stage('Test') {
            steps {
                sh 'exit 1'   // forces a red build
            }
        }
    }
}
