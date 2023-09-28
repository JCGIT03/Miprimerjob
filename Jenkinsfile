pipeline {
  agent any
  stages {
    stage('install') {
      steps {
        sh '''pwd
'''
        echo 'Comprobaciones realizadas'
        sh 'ls'
      }
    }

    stage('stop') {
      steps {
        sh 'echo "building"'
      }
    }

    stage('Unit test') {
      steps {
        sh 'echo "testing"'
      }
    }

    stage('Deploy to dev') {
      steps {
        sh 'echo "sonar"'
      }
    }

  }
}