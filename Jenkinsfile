pipeline {
  agent any
  stages {
    stage('install') {
      steps {
        sh 'systemctl apache status'
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