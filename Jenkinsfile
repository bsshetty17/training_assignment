pipeline {
  agent any
  stages {
    stage('welcome') {
      parallel {
        stage('welcome') {
          steps {
            echo 'welcome stage 1'
          }
        }

        stage('fature') {
          steps {
            echo 'added in feature branch'
          }
        }

      }
    }

  }
}