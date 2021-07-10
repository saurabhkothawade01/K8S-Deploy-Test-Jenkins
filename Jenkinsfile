pipeline {
  agent any
  stages {
    stage('git') {
      steps {
        sh "kubectl apply -f deploy.yml"
      }
    }
  }
}
