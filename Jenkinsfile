pipeline {
  agent {
    node {
      label 'demo2'
    }

  }
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/litong1103/new-job.git', branch: 'pipe3')
      }
    }

  }
  environment {
    COMPLETED_MSG = 'Build done!'
  }
}