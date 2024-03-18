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
        sh '/usr/bin/node /var/lib/jenkins/workspace/SampleJs/server.js > /var/lib/jenkins/workspace/SampleJs/temp.out '       
      }
    }    
  }
}
