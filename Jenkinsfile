pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'Test pipeline'
      }
    }
  stage('Provision VM') {
      steps {
        sh 'cd  /root/infrastructure-as-code/terraform/noncontainerized_env/' 
      }
    }
  }
}
