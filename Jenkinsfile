pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sleep 5
      }
    }
    stage('git') {
      steps {
        git 'http://test.com'
      }
    }
  }
  environment {
    branch = 'master'
  }
}