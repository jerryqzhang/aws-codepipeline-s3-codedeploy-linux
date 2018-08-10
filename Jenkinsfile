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
        git(url: 'http://test.com', branch: 'master')
      }
    }
  }
}