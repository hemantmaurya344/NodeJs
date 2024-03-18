pipeline{
  agent any
  stages{
    stage('checkout'){
      sh 'echo passed'
    }
    stage('Deploy'){
      sh 'node server.js'
    }    
}
