pipeline {
  agent any  
  stages {
    stage('Go') {
      steps {
        sh 'sudo chown $USER /var/run/docker.sock && cd /home/borbul/vector-role && molecule test'               
      }
    }
  }
}
