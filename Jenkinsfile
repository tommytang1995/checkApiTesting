pipeline {
  environment {
    registry = "sunbirdtest/cheers2019"
    registryCredential = 'dockerhub'
  }
  agent any
  stages {
    stage('Building image') {
      steps{
        sh "docker run -it --rm sunbirdtest/cheers2019"
      }
    }
  }
}
