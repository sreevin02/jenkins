pipeline {
  agent any
  tools {
    jdk 'java8'
    maven 'maven3.5'
  }
  stages {
    stage('pull') {
      steps {
        echo 'Hello'
      }
    }
    stage('Build') {
      steps {
        sh 'mvn -version'
        sh 'mvn clean'
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
