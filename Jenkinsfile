pipeline {
  agent any
  
  stages {
  
    stage('Install Dependencies') {
      steps {
         sh 'npm install'
         }
      }
      
 //   stage('deploying') {
 //     steps {
 //        sh 'sudo cp -r * /home/ubuntu/'
 //       }
 //     }
      
    stage('deploy') {
      steps {
         sh '/usr/local/bin/pm2 restart all'
         }
       }
       
     }
    }
