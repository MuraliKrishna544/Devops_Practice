pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        sh 'echo "This is build stage"'
      }
    }

    stage('Stage 2') {
      steps {
        sh 'echo "This is stage 2 test"'
      }
    }

    stage('Deploy') {
      steps {
        sh 'docker info | grep -i version'
      }
    }

  }
}