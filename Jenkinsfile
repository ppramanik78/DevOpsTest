pipeline {
  agent none
  stages {
    stage('Example Build') {
      steps {
        echo 'Hello, Maven'
        sh 'mvn --version'
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