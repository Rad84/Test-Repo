pipeline {
  agent {
    docker {
      image 'portolano/maven-3.3.9-jdk-8'
    }

  }
  stages {
    stage('Pipeline Start') {
      steps {
        echo 'Printed'
        sh 'echo "Hi"'
      }
    }
  }
}