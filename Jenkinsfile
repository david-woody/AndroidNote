pipeline {
  agent any
  stages {
    def project = 'sa-android'
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
