pipeline {
    agent any

    stages{
      stage('Deploy the application using docker-compose'){
        steps{
        sh '''
            docker-compose down
            docker-compose up -d
        '''
        }
      }
    }
}
