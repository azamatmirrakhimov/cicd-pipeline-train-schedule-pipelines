pipeline {
  agent any 
  stages {
    stage ('Build') {
      steps {
        echo 'Runing build automation'
        sh './gradlew build --no-daemon'
        sh './gradlew npm_start'
      }
    }
  }
}
