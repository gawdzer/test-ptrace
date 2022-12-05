pipeline {
  stages {
    stage('first stage') {
      steps {
        script {
          sh """
            apt-get update && apt-get install strace
            strace sleep 5
          """
        }
      }
    }
  }
}
