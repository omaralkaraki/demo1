pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Completed'
      }
    }

    stage('Testing') {
      steps {
        echo 'Testing Completed'
        timeout(time: 5)
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying Completed'
      }
    }

  }
}