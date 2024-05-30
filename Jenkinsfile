pipeline {
  agent any

  tools {
    nodejs "NODEJS" // Название NodeJS, как вы его указали в Global Tool Configuration
  }

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
        echo "Hello Deploy"
      }
    }
  }
}