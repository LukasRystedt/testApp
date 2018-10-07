pipeline {
  agent {
    docker {
      args '-v /home/debian/nodeDocker'
      image 'node:6-alpine'
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