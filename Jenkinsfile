pipeline {
  agent any
  stages {
    stage('Buzz Build') {
      steps {
        bat(script: 'dir', returnStatus: true)
      }
    }

    stage('') {
      steps {
        archiveArtifacts(artifacts: 'target/*.jar', fingerprint: true)
      }
    }

  }
}