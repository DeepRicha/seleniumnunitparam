pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat(script: '"F:\\tools\\nuget.exe" restore SeleniumNUnitParam.sln', returnStatus: true)
      }
    }
  }
}