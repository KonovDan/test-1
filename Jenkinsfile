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

    stage('yy') {
      steps {
        mail(to: 'konovdan2k04@gmail.com', subject: '1', body: '2', from: '6', mimeType: '7')
      }
    }

  }
}