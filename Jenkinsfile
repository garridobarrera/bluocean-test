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
        input(message: '�Qu� entorno elegir?', id: 'Prueba', ok: 'Pre-producci�n', submitter: 'Producci�n', submitterParameter: 'Desarrollo')
      }
    }
  }
}