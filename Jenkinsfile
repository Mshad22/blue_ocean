pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('test') {
      steps {
        echo 'one'
      }
    }

    stage('build') {
      steps {
        echo 'two'
      }
    }

    stage('deployment') {
      steps {
        echo 'three'
      }
    }

  }
}