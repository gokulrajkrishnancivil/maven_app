pipeline {
  agent any
  stages {
    stage('') {
      steps {
        sh 'mvn clean test sonar:sonar sonar:sonar -Dsonar.host.url=http://localhost:9000 -Dsonar.login=b1195e43fc430d7e16fde001e83d219cf115224d'
      }
    }

  }
}