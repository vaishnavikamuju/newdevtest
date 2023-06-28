pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'echo $PWD'
          }
        }

        stage('test') {
          steps {
            echo 'hello world'
          }
        }

      }
    }

  }
}