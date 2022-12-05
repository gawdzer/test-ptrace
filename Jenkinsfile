pipeline {
  agent any
  stages {
    stage('first stage') {
      steps {
        script {
          sh """
            whoami
            sudo whoami
          """
        }
      }
    }
  }
}
