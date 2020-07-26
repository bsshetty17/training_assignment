pipeline {
  agent any
  stages {
    stage('Buzz build') {
      agent {
        node {
          label 'linux'
        }

      }
      steps {
        sh './jenkins/build.sh'
        archiveArtifacts(artifacts: 'target/.', fingerprint: true)
      }
    }

  }
}