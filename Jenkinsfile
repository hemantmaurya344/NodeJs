pipeline{
  agent any
  stages{
    stage('checkout'){
      steps{
        sh 'echo passed'
      }
    }
    stage('Deploy'){
      steps{  
        sh 'node server.js'
      }
    }    
  }
}
