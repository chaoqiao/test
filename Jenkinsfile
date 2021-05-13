pipeline {
    agent any
    stages{
        stage('SCM Checkout'){
            steps{
                git credentialsId: 'fb671213-3457-4d2a-ad1b-0bc68c984d4e', url: 'git@github.com:chaoqiao/test.git'
            }
        }
    }
}
