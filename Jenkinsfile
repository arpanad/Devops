pipeline {
  agent {
    label "Master"
  }
  stages {
    stage('Version 1') {
      steps {
        bat 'python --version'
      }
    }
    stage('version 2') {
      steps {
        bat 'python hello.py'
      }
    }
  }
}
