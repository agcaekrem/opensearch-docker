pipeline {
  agent any
  stages{
    stage('Start container') {
      steps {
        sh 'docker compose up -d '
        sh 'docker compose ps'
      }
    }
  }
}  
