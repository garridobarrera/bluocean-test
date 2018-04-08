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
        echo 'Ejecutando junit citas'
        echo 'Ejecutando junit resto de modulos'
      }
    }
    stage('image docker') {
      steps {
        echo 'Generar imagen docker expedientes'
        echo 'Generar imagen docker notificaciones'
        echo 'Generar imagen docker tarjetas'
        echo 'Generar imagen docker avisos'
        echo 'Generar imagen docker citas'
        echo 'Generar imagen docker resto de modulos'
      }
    }
    stage('integrated test') {
      steps {
        echo 'Levantar todos los contenedores de las imagenes docker'
        echo 'Ejecutar banco de pruebas integradas'
      }
    }
    stage('deploy docker') {
      steps {
        echo 'Desplegar en repositorio imagen docker expedientes'
        echo 'Desplegar en repositorio imagen docker notificaciones'
        echo 'Desplegar en repositorio imagen docker tarjetas'
        echo 'Desplegar en repositorio imagen docker avisos'
        echo 'Desplegar en repositorio imagen docker citas'
        echo 'Desplegar en repositorio imagen docker resto de modulos'
      }
    }
    stage('deploy environment') {
      steps {
        echo 'Eleccion de entorno..... PRUEBAS, PRE-PRODUCCION, PRODUCCION'
        echo 'Desplegar imagen docker de expedientes en OpenShift'
        echo 'Desplegar imagen docker de notificaciones en OpenShift'
        echo 'Desplegar imagen docker de tarjetas en OpenShift'
        echo 'Desplegar imagen docker de avisos en OpenShift'
        echo 'Desplegar imagen docker de citas en OpenShift'
        echo 'Desplegar imagen docker de resto de modulos en OpenShift'
        
      }
    }
  }
}
