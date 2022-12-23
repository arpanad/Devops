pipeline {
  agent {
    label "Master"
  }
  stages {
    stage('Version 1') {
      steps {
        python --version
      }
    }
    stage('version 2') {
      steps {
        sh 'python --version'
      }
    }
  }
}
