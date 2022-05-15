pipeline {
    agent any
    stages {
        stages {
        stage('run') {
            steps {
                echo 'This is run step'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
    }
}