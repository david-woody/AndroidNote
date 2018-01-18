pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'Wow'
      }
    }
    stage('Build Image') {
      steps {
        sh 'docker build -t ${project} .'
      }
    }
  }
}