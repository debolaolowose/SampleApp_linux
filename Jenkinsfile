pipeline {
  agent any
  stages {
    stage('SCM') {
      steps {
          git credentialsId: 'GITHUB_ID', url: 'https://github.com/debolaolowose/SampleApp_linux.git'
          echo "Connected Successfully"
      }
    }
    stage('Testing pipeline stage 2') {
      steps {
          echo "Hello world"
      }
    }
  }
  
}
