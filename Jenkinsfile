pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo "hello world"'
      }
    }

    stage('test') {
      steps {
        echo 'Build hs been tested'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy to prod'
      }
    }

  }
}