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

    stage('second stage') {
      parallel {
        stage('second stage') {
          steps {
            echo 'stage2'
          }
        }

        stage('') {
          steps {
            archiveArtifacts(artifacts: 'target/*.jar', fingerprint: true)
          }
        }

      }
    }

  }
}