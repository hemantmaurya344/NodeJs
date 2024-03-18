pipeline{
  agent any
  stages{
    stage('checkout'){
      steps{
        sh 'echo passed'
      }
    }
    stage('Build and Deploy'){
      steps{  
        sh '/usr/bin/npm install'
        sh '/usr/bin/node server.js \\&'        
      }
    }    
  }
}
