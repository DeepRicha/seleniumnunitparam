pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat(script: 'build', encoding: 'mvn compile', returnStatus: true)
      }
    }
  }
}