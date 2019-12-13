pipeline {
  agent {
    docker {
      image 'abhidock7/springdemo'
    }

  }
  stages {
    stage('deploy') {
      agent {
        docker {
          image 'abhidock7/springdemo'
        }

      }
      steps {
        echo 'hello'
      }
    }

  }
}