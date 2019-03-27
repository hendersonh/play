pipeline {
  agent {
    docker {
      image 'node:7-alpine'
    }

  }
  stages {
    stage('Test node') {
      steps {
        sh 'echo "this is a test"'
      }
    }
    stage('List files') {
      steps {
        sh 'ls -l'
      }
    }
    stage('Say my name') {
      steps {
        sh 'echo "My name is : $USER"'
      }
    }
  }
  environment {
    USER = 'Henderson'
  }
}