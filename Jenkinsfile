pipeline {
  agent any
  environment {
      env.BRANCH_NAME
  }
  stages {
    stage('Testing pipeline') {
      steps {
          when{
              expression{
                  BRANCH_NAME == "staging"
              }
          }
          echo "Hello World"
      }
    }
    stage('Testing pipeline stage 2') {
      steps {
          echo "Hello World - 2"
      }
    }
  }
  
}
