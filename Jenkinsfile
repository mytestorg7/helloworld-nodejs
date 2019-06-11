pipeline {
  agent none
  stages {
     agent { label 'nodejs-app' } {
      steps {
        echo 'Hello World!'   
        sh 'java -version'
      }
    }
  }
}
