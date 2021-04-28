
pipeline {
agent any
  stages {
    stage('abc'){
      steps {
        sh "chmod +x deploy.yml"
        sh "kubectl apply -f deploy.yml --kubeconfig /admin.config"
      }
    }
  }

}
