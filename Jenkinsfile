pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
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