pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        parallel(
          "Hello": {
            sh 'echo Hello'
            
          },
          "Hello Date": {
            sh 'echo Hello \'date\''
            
          }
        )
      }
    }
  }
}