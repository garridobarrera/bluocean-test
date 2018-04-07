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
        input(message: 'Â¿QuÃ© entorno elegir?', id: 'Prueba', ok: 'Pre-producción', submitter: 'Pre-producción', submitterParameter: 'Desarrollo')
      }
    }
  }
}