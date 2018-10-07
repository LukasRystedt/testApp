pipeline {
  agent {
    docker {
      image 'node:8-alpine'
      args '-v -p 3000:3000'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
}