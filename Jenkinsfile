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

        stage('test') {
          steps {
            junit '**/surefire-reports/**/*.xml'
          }
        }

      }
    }

  }
}