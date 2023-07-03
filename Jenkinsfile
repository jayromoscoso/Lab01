pipeline {
  agent any
  stages {
    stage('Build Image'){
      steps {
        sh "pwd"
        sg 'docker bouild -t Lab01:10 .'
