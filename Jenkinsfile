pipeline {
  agent any
  stages {
    stage('Code Checkout') {
      git 'https://github.com/ppramanik78/DevOpsTest'
    }
     stage('Compile and Package') {
      sh 'mvn package'
     }
  }
}
