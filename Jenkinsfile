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
  }
}
