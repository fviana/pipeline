pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        parallel(
          "Test": {
            echo 'Testandoooo'
            
          },
          "Test2": {
            sh 'echo "Testandooooo"'
            
          }
        )
      }
    }
  }
  environment {
    name = 'test'
  }
}