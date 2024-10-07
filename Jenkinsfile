pipeline{
    agent{label 'main'}
    stages{
        stage('Checkout') {
            steps{
                git branch: 'main', url: 'https://github.com/matabdul/ansible_integration_lab1.git'
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
