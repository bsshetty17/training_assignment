pipeline {
  agent any
  stages {
    stage('welcome') {
      steps {
        echo 'welcome stage 1'
      }
    }

    stage('welcome 2') {
      parallel {
        stage('welcome 2') {
          steps {
            echo 'welcome stage 2'
          }
        }

        stage('welcome 2 branch') {
          steps {
            echo 'welcome 2 branch'
          }
        }

      }
    }

  }
}