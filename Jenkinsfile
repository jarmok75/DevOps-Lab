pipeline {
  agent {
    docker {
      image 'node:8-alpine'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('eka') {
      steps {
        sh 'sudo nprm install'
      }
    }

  }
}