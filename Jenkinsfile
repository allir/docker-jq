pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        timestamps()
        sh 'env'
      }
    }
  }
  environment {
    yeah = 'test'
  }
}