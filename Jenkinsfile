pipeline{
    agent any
    
    stages{
        stage("Install Dependancies"){
            steps{
                bat "npm install"
            }
        }
    }
    stage("Run UI Tests"){
        steps{
            bat "npm test"
        }
    }
}