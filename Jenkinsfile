pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello') {
      environment {
        MY_NAME = 'CMoney'
      }
      steps {
        echo "Hello ${MY_NAME}!"
        sh 'java -version'
      }
    }
  }
}