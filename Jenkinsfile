pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
    post {
        success {
            echo "Post-build (Success)"
        }
        failure {
            echo "Post-build (Failure)"
        }
        always {
            echo "Post-build (Always)"
        }
    }
}
