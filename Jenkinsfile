pipeline {
    agent any

    environment {
        TEST_URL = "google.com"
        CRED = credentials("centos-ssh")
    }

    stages {
        stage('Compile') {
            steps {
                echo 'Compile'
                echo TEST_URL
                echo CRED
            }
        }

    }
    post {
        always {
            echo 'I will always say Hello again!'
        }
    }

}
