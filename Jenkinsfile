pipeline {
  agent any
  stages {
    stage('test-env') {
      steps {
        sh 'df -h'
        sh 'cat /etc/issue'
      }
    }
  }
}