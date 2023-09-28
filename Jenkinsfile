pipeline {
  agent any
  stages {
    stage('install') {
      steps {
        sh 'sh "apt-get install apache"'
        echo 'Servicio apache instalado'
      }
    }

    stage('stop') {
      steps {
        sh 'sh "systemctl stop apache"'
        echo 'Servicio apache parado'
      }
    }

  }
}