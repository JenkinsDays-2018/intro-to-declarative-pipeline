pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello') {
      environment {
        MY_NAME = 'CMoney'
        TEST_USER = credentials('test-user')
      }
      steps {
        echo "Hello ${MY_NAME}!"
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
        sh 'java -version'
      }
    }
  }
}