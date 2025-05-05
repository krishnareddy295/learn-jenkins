pipeline {
    agent any
    options {
       ansiColor('xterm')
    }

    environment {
        TEST_URL = "google.com"

    }

    stages {
        stage('Compile') {
            steps {

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
