pipeline {
  agent any
  stages {
    stage('first stage') {
      steps {
        script {
          sh """
            whoami
            apt-get update && apt-get install strace
            strace sleep 5
          """
        }
      }
    }
  }
}
