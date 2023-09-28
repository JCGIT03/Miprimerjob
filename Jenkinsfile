pipeline {
  agent any
  stages {
    stage('install') {
      steps {
        sh 'apt-get install apache'
        echo 'Servicio apache instalado'
      }
    }

    stage('stop') {
      steps {
        sh 'systemctl stop apache'
        echo 'Servicio apache parado'
      }
    }

  }
}