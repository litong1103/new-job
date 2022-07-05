pipeline {
  agent {
    node {
      label 'demo2'
    }

  }
  stages {
    stage('Build') {
      steps {
        git 'https://github.com/litong1103/new-job.git'
      }
    }

  }
  environment {
    COMPLETED_MSG = 'Build done!'
  }
}