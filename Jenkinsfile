pipeline {
  agent any
  stages {
    stage('tet') {
      steps {
        dockerNode(image: 'nginx') {
          sh 'uname -a'
        }

      }
    }
  }
}