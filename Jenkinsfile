pipeline {
  agent any
  stages {
    stage('') {
      steps {
        parallel(
          "Check1": {
            sh 'sh "gradle clean check -x test"'
            
          },
          "Check2": {
            echo 'succuess'
            
          }
        )
      }
    }
  }
}