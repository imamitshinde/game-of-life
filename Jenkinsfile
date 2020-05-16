pipeline {
  agent any
  stages {
    stage('Clean') {
      steps {
        echo 'cleaning the ws'
      }
    }

    stage('Build') {
      steps {
        build 'Freestylejob'
      }
    }

  }
}