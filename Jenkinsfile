pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "/opt/naven/bin/mvn clean"
            }
        }
        stage('--test--') {
            steps {
                sh "/opt/naven/bin/mvn test"
            }
        }
        stage('--package--') {
            steps {
                sh "/opt/naven/bin/mvn package"
            }
        }
    }
}
