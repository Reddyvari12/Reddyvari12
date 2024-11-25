pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/Reddyvari12/Reddyvari12.git', branch: 'main')
      }
    }

    stage('Depoly') {
      steps {
        sh 'echo "hello"'
      }
    }

  }
}