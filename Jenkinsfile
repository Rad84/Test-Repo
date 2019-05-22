pipeline {
  agent {
    docker {
      image 'maven'
    }

  }
  stages {
    stage('Pipeline Start') {
      steps {
        echo 'Printed'
        sh 'echo "Hi"'
      }
    }
    stage('Build') {
      steps {
        sh 'mvn -version'
      }
    }
  }
}