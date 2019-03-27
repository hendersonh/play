pipeline {
  agent {
    docker {
      image 'maven:3-alpine'
    }

  }
  stages {
    stage('Test') {
      steps {
        sh '''node --version
df -h'''
      }
    }
  }
}