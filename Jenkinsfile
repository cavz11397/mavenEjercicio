pipeline {
  agent any
  stages {
    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

    stage('email') {
      steps {
        emailext(body: 'prueba', subject: 'prueba', to: 'cristian_vasquez82152@elpoli.edu.co', saveOutput: true)
        echo 'send email'
      }
    }

  }
}