pipeline {
  agent {
    node {
      label 'node'
    }

  }
  stages {
    stage('Checkout') {
      steps {
        isUnix()
      }
    }
    stage('Test') {
      steps {
        sh '''sh \'node -v\'


'''
      }
    }
  }
  environment {
    NODE_ENV = 'test'
  }
}