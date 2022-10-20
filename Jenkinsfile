pipeline {
  agent any
  stages {
    stage('Hello') {
      parallel {
        stage('Hello') {
          steps {
            echo 'Hello World'
          }
        }

        stage('Hello 2') {
          steps {
            echo 'Hello again! No error!'
          }
        }

      }
    }

  }
}