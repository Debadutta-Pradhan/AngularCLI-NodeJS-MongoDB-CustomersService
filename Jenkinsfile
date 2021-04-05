pipeline {
    agent any

    stages{
      stage('Deploy the application using docker-compose'){
        steps{
        sh 'sudo docker-compose build'
        sh 'sudo docker-compose up -d'
   
        }
      }
    }
}
