pipeline {
    agent any

    environment {
        TEST_URL = "google.com"
    }

    stages {
        stage('Compile') {
            steps {
                echo 'Compile'
                echo TEST_URL
            }
        }

    }
    post {
        always {
            echo 'I will always say Hello again!'
        }
    }

}
