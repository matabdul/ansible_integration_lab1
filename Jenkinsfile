pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps{
                git branch: 'main', url: 'https://github.com/matabdul/ansible_integration_lab1'
            }
        } 
        stage('Setup'){
            steps{
                sh 'echo setting up jenkins integration!'
            }
        }
        stage('Test'){
            steps{
                sh 'echo Testing up jenkins integration!'
            }
        }
    }
}
