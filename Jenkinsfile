pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'g++ main.cpp -o main'
      }
    }
    stage('test') {
      steps {
        sh './main'
      }
    }
  }
}