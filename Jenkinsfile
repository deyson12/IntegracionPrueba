pipeline {
  agent any
  stages {
    stage('Prepare') {
      steps {
        echo 'Se inicializa el proyecto'
        emailext(subject: 'Hola', body: 'Hola', to: 'deyson12@gmail.com', replyTo: 'deyson12@gmail.com')
      }
    }
  }
}