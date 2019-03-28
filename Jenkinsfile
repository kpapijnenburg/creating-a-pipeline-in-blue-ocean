pipeline {
  agent {
    docker {
      image 'node:6-alipine'
      args '-p 3000:3000'
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