pipeline {
  agent any
  stages {
    stage('script') {
      steps {
        sh 'ls -la'
      }
    }

    stage('checkout') {
      steps {
        git(url: 'https://github.com/Har5H-Ag/livechat-example', branch: 'main')
      }
    }

  }
}