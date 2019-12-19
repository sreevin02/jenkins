pipeline {
  agent any
  stages {
    stage('pull') {
      steps {
        echo 'Hello'
      }
    }
    stage('Build') {
      steps {
        sh 'mvn --version'
        sh 'git --version'
      }
    }
    stage('deploy') {
      steps {
        echo 'deployed'
      }
    }
  }
}
