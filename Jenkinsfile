pipeline {
  agent any
  stages {
    stage('myStage'){
      steps {
        sh 'ls -la' 
      }
    }
    stage('ssh'){
      steps{
        ssh -l sohaib 172.16.2.24 "secrete; netstat"
        
      }
    }
    stage('Build') {
      steps { 
        sh 'ls' 
      }
    }
  }
}
