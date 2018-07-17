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
        stage('Example test') {
            steps {
                bat "mvn test"
            }
        }
        stage('Example package') {
            steps {
                bat "mvn package"
            }
        }
    }
}
