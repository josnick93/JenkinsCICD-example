pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''cd devops_ci/billing/
mvn clean install'''
      }
    }

  }
}