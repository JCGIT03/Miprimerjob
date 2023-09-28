pipeline {
  agent any
  stages {
    stage('install') {
      steps {
        sh 'sudo apt-get install apache'
        echo 'Servicio apache instalado'
      }
    }

    stage('stop') {
      steps {
        sh 'sudo systemctl stop apache'
        echo 'Servicio apache parado'
      }
    }

  }
}