pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        sh 'go test ./...'
        sh 'go test ./..'
      }
    }

  }
}