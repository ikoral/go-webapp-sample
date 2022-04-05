pipeline {
  agent any
  tools{
       go 'go-1.17'
   }
   environment{
       G0111MODULE='on'
   }
  stages {
    stage('dev') {
      steps {
        sh 'go test ./...'
      }
    }

  }
}
