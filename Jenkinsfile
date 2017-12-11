pipeline {
  agent any
  stages {
    stage('First') {
      parallel {
        stage('First') {
          steps {
            sleep(unit: 'MINUTES', time: 1)
          }
        }
        stage('Second') {
          steps {
            echo 'This Second!'
          }
        }
      }
    }
  }
}