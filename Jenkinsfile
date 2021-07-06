pipeline {
  agent any
  stages {
    stage('build synapse') {
      steps {
        sh 'docker build docker/Dockerfile -t pankaj/test:latest'
      }
    }

  }
}