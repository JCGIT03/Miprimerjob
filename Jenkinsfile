pipeline {
  agent any
  stages {
    stage('install') {
      steps {
        sh 'sudo -S admin apt-get install apache'
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