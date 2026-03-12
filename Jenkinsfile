pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo "Build stage started"
            }
        }

        stage('Test') {
            steps {
                sh './test.sh'
            }
        }

        stage('Deploy') {
            steps {
                sh './app.sh'
            }
        }

    }
}
