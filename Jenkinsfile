pipeline {
  agent any
  stages {
    stage('Build Image'){
      steps {
        sh "pwd"
        sg 'docker build -t Lab01:10 .'
      }
    }
  }
}
