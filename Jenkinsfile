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
        input(message: '¿Qué entorno elegir?', id: 'Prueba', ok: 'Pre-producci�n', submitter: 'Pre-producci�n', submitterParameter: 'Desarrollo')
      }
    }
  }
}