def echoNodeEnvironment() {
  echo "NODE_NAME = ${NODE_NAME}"
}

pipeline {
  agent any
  stages {
    stage('Echo node environment') {
      steps {
        script {
          echoNodeEnvironment();
        }
      }
    }
  }
}