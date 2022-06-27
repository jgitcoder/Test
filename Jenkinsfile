pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        sh '''date
pwd'''
      }
    }

    stage('Test') {
      steps {
        sh 'hostname'
        echo 'This is Test stage'
      }
    }

    stage('Build') {
      steps {
        echo 'Build Image'
        sleep 10
      }
    }

    stage('Deploy ') {
      steps {
        echo 'Project is live now'
      }
    }

  }
}