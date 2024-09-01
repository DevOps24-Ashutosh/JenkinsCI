pipeline {
  agent {
    docker { image 'node:16-alpine' }
  }
  stages {
    stage('Clean Workspace') {
        steps {
            cleanWs()
        }
    }
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
  }
}
