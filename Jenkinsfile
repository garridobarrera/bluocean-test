pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        echo 'Descargar codigo de SVN'
        echo 'Compilando servicio expedientes'
        echo 'Compilando servicio notificaciones'
        echo 'Compilando servicio tarjetas'
        echo 'Compilando servicio avisos'
        echo 'compilando servicio citas'
        echo 'Compilando resto de modulos'
      }
    }
    stage('unit test') {
      steps {
        echo 'Ejecutando junit expedientes'
        echo 'Ejecutando junit notificaciones'
        echo 'Ejecutando junit tarjetas'
        echo 'Ejecutando junit avisos'
        echo 'Ejecutando junit resto de modulos'
      }
    }
    stage('image docker') {
      steps {
        echo 'generate image docker'
      }
    }
    stage('integrated test') {
      steps {
        echo 'running integrated test'
      }
    }
    stage('deploy docker') {
      steps {
        echo 'deploy image docker'
      }
    }
    stage('deploy environment') {
      steps {
        echo 'Deploy images docker in environment'
      }
    }
  }
}