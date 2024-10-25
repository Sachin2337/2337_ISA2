pipeline {
    agent any

    stages {
        stage('Build docker image'){
            steps{
                 bat 'docker build -t  sachin2337/2337_isa2 .'
            }
        }
        stage('Build and run contaner'){
            steps{
                bat 'docker run -d -it  sachin2337/2337_isa2'
            }
        }
        
    }
}
