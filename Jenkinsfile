pipeline {
  agent {
    label "Master"
  }
  stages {
    stage('hello') {
      steps {
        'python --version'
      }
    }
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
  }
}
