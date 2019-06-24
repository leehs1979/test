pipeline {
  agent {
    node {
      label 'pipeline-build'
    }

  }
  stages {
    stage('ToOCP') {
      agent {
        node {
          label 'pipeline-build'
        }

      }
      steps {
        echo 'OCP'
      }
    }
  }
}