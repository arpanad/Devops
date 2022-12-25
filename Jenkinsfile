pipeline {
  agent {
    label "Master"
  }
  triggers {
        cron('H * * * *')
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
