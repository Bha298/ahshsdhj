pipeline{
    agent any
    stages{
         stage('Git Checkout'){
            steps{
            git branch: 'main', url: 'https://github.com/Bha298/ahshsdhj.git'
            }
         }
         stage('Unit testing '){
            steps{
                    sh 'mvn test'
            }
         }
         }
         }
