pipeline {
  agent any
  stages {
    stage('print_user_name') {
      parallel {
        stage('print_user_name') {
          steps {
            sh 'echo "My name $USER"'
          }
        }
        stage('show top') {
          steps {
            sh 'top'
          }
        }
      }
    }
  }
}