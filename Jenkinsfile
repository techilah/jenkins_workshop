pipeline {
  agent {
    node {
      label 'built-in'
    }

  }
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

    stage('Execute script') {
      steps {
        sh 'dir'
      }
    }

  }
}