pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo "building"
        sleep 10
      }
    }
    stage('Test') {
      steps {
        echo "testing changes"
        sleep 30
      }
    }
    stage('Deploy') {
      steps {
        echo "deploying"
      }
    }
  }
}
