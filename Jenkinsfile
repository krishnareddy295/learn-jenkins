pipeline {
    agent any

    environment {
        TEST_URL = "google.com"
        SERVICE_CREDS = credentials('my-predefined-username-password')
    }

    stages {
        stage('Compile') {
            steps {
                echo 'Compile'
                echo TEST_URL
                sh echo $SERVICE_CREDS
            }
        }

    }
    post {
        always {
            echo 'I will always say Hello again!'
        }
    }

}
