pipeline{
    agent any

    stages{
        stage('Deploy the application using docker-compose')
        sh '''
            docker-compose down
            docker-compose up -d
        '''
    }
}
