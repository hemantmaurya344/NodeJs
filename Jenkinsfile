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
        sh 'npm install'
        sh 'sh runJs.sh'        
      }
    }    
  }
}
