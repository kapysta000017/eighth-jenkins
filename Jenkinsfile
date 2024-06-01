pipeline {
  agent any

  stages {
    stage("Deploy") {
      steps {
        sshagent(['Anahi']) {
          sh 'ssh -o StrictHostKeyChecking=no -l root ubuntu@45.89.189.30 uname -a'
          // sh 'scp -o StrictHostKeyChecking=no index.html root ubuntu@45.89.189.30:/var/www/html'
        }
      }
    }
  }
}
