pipeline {
  agent any
  stages {
    stage('msg') {
      parallel {
        stage('msg') {
          steps {
            echo 'Hello World'
          }
        }

        stage('sleep') {
          steps {
            sleep 3
          }
        }

      }
    }

  }
}