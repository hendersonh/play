pipeline {
  agent {
    docker {
      image 'node:7-alpine'
    }

  }
  stages {
    stage('Pull node:7-alpine image') {
      steps {
        sh '''node --version
df -h'''
      }
    }
  }
}