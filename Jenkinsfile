pipeline {
  agent any
  stages {
    stage('initialize') {
      parallel {
        stage('initialize') {
          steps {
            echo 'this is a minim'
          }
        }

        stage('build') {
          steps {
            bat 'mvn'
          }
        }

      }
    }

    stage('compile') {
      steps {
        bat 'mvn compile'
      }
    }

  }
}