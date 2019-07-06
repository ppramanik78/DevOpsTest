pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build(job: 'Firstbuild', wait: true)
      }
    }
  }
}