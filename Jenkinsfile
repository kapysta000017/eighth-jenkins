pipeline {
  agent any

  stages {
    stage("Deploy") {
      steps {
        sshagent(['Anahi']) {
          // sh 'scp -o StrictHostKeyChecking=no -r ./index.html root@45.89.189.30:/var/www/html'
          sh 'ssh -o StrictHostKeyChecking=no 45.89.189.30 uname -a'
        }
      }
    }
  }
}