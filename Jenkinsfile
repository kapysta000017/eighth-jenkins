pipeline {
  agent any

  stages {
    stage("Deploy") {
      steps {
        sshagent(['Anahi']) {
          // sh 'scp -o StrictHostKeyChecking=no -r ./index.html root@45.89.189.30:/var/www/html'
          // sh 'ssh -tt -o StrictHostKeyChecking=no ubuntu@45.89.189.30 ls'
          sh 'ssh -o StrictHostKeyChecking=no -l root ubuntu@45.89.189.30 uname -a'
        }
      }
    }
  }
}