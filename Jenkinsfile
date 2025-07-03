pipeline{
    agent any
    tools{
        maven 'maven'
    }
    stages{
        stage("pull from src"){
            steps{
                git branch:'main', url:'https://github.com/Nk5302/tasktest.git'
            }
        }
        stage("maven clean"){
              steps{
                  sh 'mvn clean'
              }
        }
        stage("maven package"){
            steps{
                sh 'mvn package'
            }
        }     
    }
}
