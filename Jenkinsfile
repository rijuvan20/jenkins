pipeline {
  agent any
  stages {
    stage('Buzz Build') {
      steps {
        bat(script: 'dir', returnStatus: true)
        powershell 'ls'
      }
    }

  }
}