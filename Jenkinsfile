pipeline {
  agent {
    docker {
      image 'nginx'
      args 'latest'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        sh 'ls'
      }
    }
    stage('deploy') {
      steps {
        sh 'echo deploy'
      }
    }
  }
}