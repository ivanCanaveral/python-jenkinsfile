pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'echo "Testing with python ..."'
                sh 'python --version'
                sh 'sleep 5'
            }
        }
    }
}