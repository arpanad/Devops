pipeline {
  agent {
    label "Master"
  }
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
