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
        echo 'Project3'
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