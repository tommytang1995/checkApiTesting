pipeline {
  environment {
    registry = "sunbirdtest/cheers2019"
    registryCredential = 'dockerhub'
  }
  agent any
  stages {
    stage('Building image') {
      steps{
        sh "docker run --tty --rm sunbirdtest/cheers2019"
      }
    }
  }
}
