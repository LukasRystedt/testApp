pipeline {
  agent {
    docker {
      image 'node:8-alpine'
      args '-v /home/debian/nodeDocker'
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