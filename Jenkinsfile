pipeline {
    agent any
    environment {
       SONAR_CREDS = credentials('DOCKER_CREDS')
    }
    stages {
        stage ('this is credentials example') {
            steps {
                echo "username is ${SONAR_CREDS_USR}"
                echo "password is ${SONAR_CREDS_PSW}"
            }
        }
    }
}
