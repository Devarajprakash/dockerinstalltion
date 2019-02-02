pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'building now'
      }
    }
    stage('testing') {
      parallel {
        stage('testing') {
          steps {
            sh 'echo "testing the blueocean"'
          }
        }
        stage('testing chroime') {
          steps {
            sh 'echo "testing the blueocean"'
          }
        }
        stage('') {
          steps {
            sh 'echo "testing the bn"'
          }
        }
      }
    }
    stage('deployment') {
      steps {
        sh 'echo "deploing"'
      }
    }
  }
}