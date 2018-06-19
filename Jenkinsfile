pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('build') {
            steps {
                bat 'mvn --version'
            }
        }
        
        stage('Test') {
            steps {
                bat 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                bat 'Deploying....'
                bat 'mvn --version'
             }
         }
    }
}
