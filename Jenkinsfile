pipeline {
  agent any
  stages {
    stage('print_user_name') {
      steps {
        sh 'echo "My name $USER"'
      }
    }
    stage('list files') {
      steps {
        sh 'ls -l'
      }
    }
  }
}