pipeline {
    agent any

    stages {
        
        stage('Build') {
            steps {
                script{
                powershell 'mvn clean install'
                }
            }
        }

        stage('Test') {
            steps {
                script{
                powershell 'mvn test'
                }
            }
        }
    }
}
