pipeline {
  agent any
  stages {
    stage('initialize') {
      steps {
        echo 'this is a minim'
      }
    }

    stage('compile') {
      steps {
        bat 'mvn compile'
      }
    }

  }
}