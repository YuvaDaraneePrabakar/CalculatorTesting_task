pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                bat 'git clone https://github.com/YuvaDaraneePrabakar/CalculatorTesting_task.git'
            }
        }
        
        stage('Build') {
            steps {
                bat 'mvn compile'
            }
        }

        stage('Test') {
            steps {
                bat 'mvn clean test'
            }
        }
    }
}
