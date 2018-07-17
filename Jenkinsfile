pipeline {
    agent any
    stages {
        stage('Example clean') {
            steps {
                bat "mvn clean"
            }
        }
        stage('Example install') {
            steps {
                bat "mvn install"
            }
        }
        stage('Example Build') {
            steps {
                bat "mvn build"
            }
        }
        stage('Example test') {
            steps {
                bat "mvn test"
            }
        }
    }
}
