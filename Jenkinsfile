pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh './gradlew init'
                sh './gradlew npm_start'
            }
        }
    }
}
