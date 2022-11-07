pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'This is a minimal pipeline.'
        sh 'mvn -B -DskipTests clean package'
      }
    }

  }
}
