pipeline {
  agent {
    docker {
      args '-v $HOME/.m2:/root/.m2'
      image 'node:8-alpine'
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