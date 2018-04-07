pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sleep 10
      }
    }
    stage('hola') {
      steps {
        echo 'Esto es una prueba'
        input(message: 'Como te llamas', id: 'CHEMA', ok: 'CHEMA')
      }
    }
  }
}