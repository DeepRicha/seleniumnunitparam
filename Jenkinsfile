pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat(script: 'mvn compile', returnStatus: true)
      }
    }
  }
}