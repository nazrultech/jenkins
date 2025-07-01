pipeline {
  agent any
  stages {
    stage('pre-build') {
      steps {
        sh '''echo "present directory"
sh \'pwd\''''
      }
    }

    stage('build') {
      steps {
        echo 'build'
      }
    }

  }
  environment {
    dev = 'dev'
  }
}