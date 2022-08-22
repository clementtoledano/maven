pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                withMaven(maven: 'maven3') {
                    echo 'foo'
                    sh 'mvn clean install'
                    echo 'bar'
                }
            }
        }
    }
}

