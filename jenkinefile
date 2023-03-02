pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Test') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
  
post 
  {
    always 
    {
      emailext body: 'summary', replyTo: 'skshirod25@gmail.com', subject: 'pipeline - notify', to: 'skshirod25@gmail.com'
    }
  }
}
