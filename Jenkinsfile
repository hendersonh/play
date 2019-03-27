pipeline {
  agent {
    docker {
      image 'maven:3-alpine'
    }

  }
  stages {
    stage('back-end') {
      steps {
        sh 'mvn --version'
      }
    }
  }
}