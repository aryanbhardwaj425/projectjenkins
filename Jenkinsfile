pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add testing steps here, e.g.:
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
              
            }
        }
    }
    post {
        always {
            echo 'Pipeline complete'
        }
        success {
            echo 'Pipeline succeeded'
        }
        failure {
            echo 'Pipeline failed'
        }
    }
}
