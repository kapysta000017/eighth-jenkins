pipeline {
  agent any

  stages {
    stage("Deploy") {
      steps {
        sshagent (credentials: ['selectel']) {
          sh 'scp -o StrictHostKeyChecking=no -r * ubuntu@45.89.188.57:/var/www/html'
        }
      }
    }
  }
}