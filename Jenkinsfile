pipeline { 
    agent any 
    stages {
        stage('Build') { 
            steps { 
                sh 'mvn test' 
            }
        }
        stage('Test'){
            steps {
                sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                sh 'mvn build'
            }
        }
    }
}
