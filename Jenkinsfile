pipeline {
  agent any
  stages {
    stage('download the code') {
      parallel {
        stage('download the code') {
          steps {
            echo 'This is downloading code '
          }
        }

        stage('Download 2nd code') {
          steps {
            echo 'Download the 2nd code'
          }
        }

      }
    }

    stage('build the code ') {
      steps {
        echo 'this is build the code '
      }
    }

    stage('testing') {
      steps {
        echo 'testing phase'
      }
    }

    stage('deployment') {
      steps {
        echo 'this is deployment stage '
      }
    }

  }
}