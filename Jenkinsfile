pipeline {
  agent any
  
  stages {
  
    stage('Install Dependencies') {
      steps {
         sh 'npm install'
         }
      }
      
 //   stage('pm2 install') {
 //     steps {
 //        sh 'sudo npm i pm2 -g'
 //       }
 //     }
      
    stage('deploy') {
      steps {
         sh 'pm2 restart all'
         }
       }
       
     }
    }
