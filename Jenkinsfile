pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pwd
date'''
      }
    }

    stage('Test') {
      steps {
        echo 'TestStep'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
        sleep 13
      }
    }

  }
}