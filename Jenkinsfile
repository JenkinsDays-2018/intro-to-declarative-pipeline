pipeline {
  agent {
    label 'jdk9'
  }
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
}