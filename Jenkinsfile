pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh 'env'
        cleanWs()
      }
    }
  }
  environment {
    yeah = 'test'
  }
}