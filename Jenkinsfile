pipeline {
  agent any
    stage('Start container') {
      steps {
        sh 'docker compose up -d '
        sh 'docker compose ps'
      }
    }
}
