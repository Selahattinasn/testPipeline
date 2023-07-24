pipeline {
    agent any
    stages{
        stage("hello"){
            steps{
                echo "Hi"
               
               
            }
        }
        stage("who"){
            steps{
                
                sh "whoami"
                
            }
        }
         stage("time"){
             steps{
                
                
                sh "uptime"
            }
        }
         
    }
}