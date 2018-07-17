pipeline {
    agent any
    stages {

        stage('compile'){
          steps{
                sh 'mvn build'
                }
        }
        stage('build'){
          steps{
                sh 'mvn test'
                }
        }

}
}
