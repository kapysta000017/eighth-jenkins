pipeline {
  agent { docker { image "node:latest" } }

  stages {
    stage("Build") {
      steps {
        echo "Hello Build"
      }
    }
    stage("Test") {
      steps {
        echo "Hello Test"
      }
    }
    stage("Deploy") {
      steps {
        sh "node --version"
        echo "Hello Deploy"
      }
    }
  }
}