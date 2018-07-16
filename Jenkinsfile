pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'this is my file'
          }
        }
        stage('test') {
          steps {
            echo 'this is test file'
          }
        }
        stage('deploy') {
          steps {
            echo 'this is deploy file'
          }
        }
      }
    }
  }
}