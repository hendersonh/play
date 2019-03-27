pipeline {
  agent any
  stages {
    stage('pull nginx') {
      steps {
        dockerNode(image: 'nginx') {
          sh 'echo date'
        }

      }
    }
  }
}