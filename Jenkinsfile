pipeline {
  agent { label 'agent' }

  stages {
    stage('Build') {
      steps {
        sh 'echo Running build on Jenkins Agent Node'
      }
    }
    stage('Test') {
      steps {
        sh 'echo Test stage running on agent'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo Deploy stage running on agent'
      }
    }
  }
}
