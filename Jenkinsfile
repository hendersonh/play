pipeline {
  agent {
    docker {
      image 'node:7-alpine'
    }

  }
  stages {
    stage('Pull node:7-alpine image') {
      steps {
        sh 'echo "this is a test"'
      }
    }
  }
}