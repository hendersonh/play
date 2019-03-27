pipeline {
  agent {
    docker {
      image 'nginx'
    }

  }
  stages {
    stage('Back-end') {
      agent {
        docker {
          image 'maven:3-alpine'
        }

      }
      steps {
        sh 'mvn --version'
      }
    }
    stage('Front-end') {
      agent {
        docker {
          image 'node:7-alpine'
        }

      }
      steps {
        sh 'node --version'
      }
    }
    stage('web-server') {
      agent {
        docker {
          image 'ubuntu'
        }

      }
      steps {
        sh 'uname -n'
      }
    }
  }
}