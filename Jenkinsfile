pipeline {
    agent any

    environment {
        TEST_URL = "google.com"

    }

    stages {
        stage('Compile') {
            steps {

               echo TEST_URL
               echo env

            }
        }

    }
    post {
        always {
            echo 'I will always say Hello again!'
        }
    }

}
