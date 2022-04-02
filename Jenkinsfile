pipeline {
  agent any
  stages {
    stage('Saludo') {
      steps {
        echo 'Hola desde Blue Ocean - Pipe Creator'
      }
    }

    stage('Environment') {
      steps {
        sh 'env'
      }
    }

    stage('Exit') {
      steps {
        echo 'Terminando proyecto'
      }
    }

    stage('Ultimo_mov') {
      steps {
        echo 'Se agrega stage al proyecto'
      }
    }

  }
}
