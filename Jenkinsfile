pipeline {
  agent any
  stages {
    stage('install maven') {
      steps {
        sh '''
sudo su'''
        sh 'echo ${password}'
        sh 'apt-get install maven'
      }
    }

    stage('') {
      steps {
        sh 'mvn build'
      }
    }

  }
  environment {
    password = 'Rahul474.'
  }
}