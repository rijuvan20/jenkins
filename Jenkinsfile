pipeline {
  agent any
  stages {
    stage('Hello World') {
      agent any
      steps {
        echo 'Welcome !'
      }
    }

    stage('Bees Bees') {
      steps {
        echo 'Bees Bees'
      }
    }

    stage('Fluffy Build') {
      steps {
        echo 'Placeholder'
        sh 'echo Another Placeholder'
      }
    }

    stage('Fluppy Test') {
      steps {
        sh '''sleep 5
echo Success!'''
      }
    }

    stage('Fluppy Deploy') {
      steps {
        echo 'Placeholder'
      }
    }

  }
}