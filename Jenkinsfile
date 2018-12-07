pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Hi there!'
      }
    }
    stage('Test') {
      steps {
        sh 'ls /'
      }
    }
  }
}
