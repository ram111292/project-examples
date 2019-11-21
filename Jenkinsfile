pipeline {
  agent any
  stages {
    stage('checkout') {
      parallel {
        stage('checkout') {
          steps {
            git(url: 'https://github.com/ram111292/project-examples.git', branch: 'master')
          }
        }
        stage('checkout2') {
          steps {
            git(url: 'https://github.com/ram111292/redux.git', branch: 'master')
          }
        }
      }
    }
  }
}