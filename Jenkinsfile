pipeline {
  agent { node { label 'slave-build-node' } }
  
  stages {
  
    stage('Install Dependencies') {
      steps {
         sh 'npm install'
         }
      }
      
    //stage('pm2 install') {
      //steps {
         //sh 'sudo npm i pm2 -g'
         //}
      //}
      
    stage('deploy') {
      steps {
         sh 'node index.js'
         }
       }
       
     }
    }
