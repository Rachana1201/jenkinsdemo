pipeline {
    agent any

    stages {
        stage('Hello123.......') {
            steps {
                echo 'Hello, Jenkins!'
            }
        }

        stage('Date') {
            steps {
                sh 'date'
            }
        }

        stage('Build') {
            steps {
                echo 'Build completed successfully....!'
            }
        }
    }

    post {
        success {
             echo 'Pipeline executed successfully'
        }
        failure {
            echo 'Pipeline failed'
        }
    }
}

