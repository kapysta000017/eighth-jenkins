pipeline {
  agent any

  stages {
    stage("Deploy") {
      steps {
        sshagent(['Anahi']) {
          sh 'scp -o StrictHostKeyChecking=no -r ./index.html ubuntu@45.89.189.30:/var/www/html'
        }
      }
    }
  }
}