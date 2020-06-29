pipeline {
  agent none
  stages {
    stage('Example Build') {
      agent any
      steps {
        echo 'Hello, Maven'
        bat 'mvn --version'
      }
    }
    stage('Example Test') {
      agent {
        docker 'openjdk:8-jre'
      }
      steps {
        echo 'Hello, JDK'
        sh 'java -version'
      }
    }
  }
}