pipeline {
  agent any
  triggers {
    pollSCM '* * * * *'
  }
  stages {
    stage('checkout code') {
      steps {
        git(url: 'https://github.com/ultimitech/uts37', branch: 'main')
      }
    }

    stage('log') {
      steps {
        sh 'ls -la'
        sh 'ping x'
      }
    }

  }
}
