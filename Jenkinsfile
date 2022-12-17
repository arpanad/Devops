pipeline {
  agent any
  stages {
    stage('hello') {
      steps {
        sh 'python hello.py'
      }
    }
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
  }
}
