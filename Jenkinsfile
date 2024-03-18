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
        echo "Build"
        sh '/usr/bin/npm install'
        sh 'ls'
        sh 'node server.js &'        
      }
    }    
  }
}
