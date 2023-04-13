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

        stage('new branch') {
          steps {
            echo 'there'
          }
        }

      }
    }

  }
}