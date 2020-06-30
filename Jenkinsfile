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
      agent any
      steps {
        echo 'Hello, JDK'
        bat 'java -version'
      }
    }
  }
}