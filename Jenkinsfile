pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'dafdafdf'
      }
    }
    stage('yet another') {
      steps {
        echo 'test'
      }
    }
    stage('failed') {
      steps {
        sh 'false'
      }
    }
  }
}