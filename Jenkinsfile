pipeline {
      agent any
      
      stages {
          stage('Deploy'){
             steps{
                 sh 'sudo systemctl start docker'
                 sh 'sudo docker-compose up -d'
                  }
                          }
              }
          } 
