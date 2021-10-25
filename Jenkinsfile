
pipeline {
    agent any
    stages{
        stage ("Git Checkout"){
            steps{
                git ''
            }
        }
        stage ("Maven Build"){
            steps{
            sh 'mvn clean install package'
            }
        } 
        stage ("webhook stage"){
            steps{
            echo 'welocme to webhooks'
            }
        }
    }
}
