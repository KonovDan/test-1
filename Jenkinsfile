pipeline {
  agent any
  stages {
    stage('Check code') {
      steps {
        git(url: 'https://github.com/KonovDan/test-1.git', branch: 'main')
      }
    }

    stage('error') {
      steps {
        sh 'ls'
      }
    }

  }
}