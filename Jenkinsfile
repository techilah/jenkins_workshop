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

        stage('') {
          steps {
            echo 'Hello again'
          }
        }

      }
    }

  }
}