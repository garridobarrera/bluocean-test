pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sleep 10
        svn 'svn://localhost'
      }
    }
    stage('hola') {
      steps {
        echo 'Esto es una prueba'
        input(message: 'Â¿QuÃ© entorno elegir?', id: 'Prueba', ok: 'Prueba', submitter: 'admin', submitterParameter: 'Desarrollo')
      }
    }
  }
}