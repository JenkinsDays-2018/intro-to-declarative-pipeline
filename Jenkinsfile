pipeline {
  agent any
  stages {
    stage('Hello World!') {
      parallel {
        stage('Hello World!') {
          steps {
            echo 'Hello World!'
          }
        }
        stage('Java version') {
          steps {
            sh 'java -version'
          }
        }
      }
    }
  }
  environment {
    jdk9 = 'jdk9'
  }
}