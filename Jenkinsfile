pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build stage started'
                sh 'python3 app.py'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage started'
                sh 'python3 test_app.py'
            }
        }
    }
}
