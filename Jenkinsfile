pipeline {
  agent any
  stages {
    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

    stage('') {
      steps {
        emailext(body: 'prueba', subject: 'prueba', to: 'cristian_vasquez82512@elpoli.edu.co')
        echo 'send email'
      }
    }

  }
}