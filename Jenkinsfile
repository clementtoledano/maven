pipeline {
  agent any
  stages {
    stage("maven install") {
      steps {
        withMaven(maven: "maven3") {
            echo 'foobar'
            sh 'mvn clean install'
            echo 'foobar'
          }
      }
    }
  }
}