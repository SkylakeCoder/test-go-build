pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '/usr/local/go/bin/go build'
      }
    }

  }
  environment {
    env = 'test'
  }
}