pipeline {
    agent any
    stages {
        stage('Example clean') {
            steps {
                sh "rm -rf my-app"
                sh "git clone https://github.com/pknowledge/my-app.git"
                sh "mvn clean -f my-app"
            }
        }
        stage('Example install') {
            steps {
                sh "mvn install -f my-app"
            }
        }
        stage('Example test') {
            steps {
                sh "mvn test -f my-app"
            }
        }
        stage('Example package') {
            steps {
                sh "mvn package -f my-app"
            }
        }
    }
}
