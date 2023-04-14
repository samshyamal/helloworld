pipeline {
  agent any
  stages {
    stage('helloworld') {
      parallel {
        stage('helloworld') {
          steps {
            echo 'helloworld'
          }
        }

        stage('hey') {
          steps {
            echo 'hey'
          }
        }

      }
    }

    stage('manual input') {
      steps {
        input(message: 'manual input', ok: 'yes')
      }
    }

  }
}