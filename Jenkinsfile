pipeline {
    agent any

    environment {
        TEST_URL = "google.com"
        SSH = credentials("centos-ssh")
    }

    stages {
        stage('Compile') {
            steps {

               echo TEST_URL
               echo SSH
            }
        }

    }
    post {
        always {
            echo 'I will always say Hello again!'
        }
    }

}
