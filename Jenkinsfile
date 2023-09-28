pipeline {
  agent any
  stages {
    stage('install') {
      steps {
        sh '''sudo -S  apt-get install apache /



admin'''
        echo 'Servicio apache instalado'
      }
    }

    stage('stop') {
      steps {
        sh 'sudo -S admin systemctl stop apache'
        echo 'Servicio apache parado'
      }
    }

  }
}