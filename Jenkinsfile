pipeline {
    agent any
    environment {
       MY_CREDS = credentials('nexus-creds')
    }
    stages {
        stage ('this is credentials example') {
            steps {
                echo "username is ${MY_CREDS_USR}"
                echo "password is ${MY_CREDS_PSW}"
            }
        }
    }
}
