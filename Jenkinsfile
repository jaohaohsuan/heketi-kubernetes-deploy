pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        parallel(
          "build": {
            sh 'du -sh .'
            
          },
          "test": {
            echo 'let\'s test'
            
          }
        )
      }
    }
  }
}