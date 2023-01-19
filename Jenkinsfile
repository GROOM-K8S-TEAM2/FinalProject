pipeline {
  agent any
  stages {
    stage ('verify version') {
      steps {
        sh 'php --version'
      }
    }
    stage ('final') {
      steps {
        sh 'php index.php'
      }
    }
  }
}
