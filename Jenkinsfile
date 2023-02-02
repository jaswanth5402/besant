pipeline {
  agent any
  stages {
    stage('download') {
      steps {
        nodejs('my-node') {
          sh 'npm insatll'
        }

      }
    }

    stage('build') {
      steps {
        nodejs('my-node') {
          sh 'ng build'
        }

      }
    }

  }
}