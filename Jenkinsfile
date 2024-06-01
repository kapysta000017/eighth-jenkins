pipeline {
  agent any

  stages {
    stage("Deploy") {
      steps {
        sshagent (credentials: ['selectel-shawna']) {
          sh 'ssh -o StrictHostKeyChecking=no -l cloudbees 45.89.188.57 uname -a'
        }
      }
    }
  }
}