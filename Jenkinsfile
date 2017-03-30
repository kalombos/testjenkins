pipeline {
  agent any
  stages {
    stage('Install dependencies') {
      steps {
        sh 'npm install'
      }
    }
    stage('Run server') {
      steps {
        sh 'npm start'
      }
    }
  }
}