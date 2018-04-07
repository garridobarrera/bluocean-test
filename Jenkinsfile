pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        echo 'Compiling....'
      }
    }
    stage('unit test') {
      steps {
        echo 'unit test'
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