pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                withMaven {
                    echo 'foo'
                    sh 'mvn clean verify'
                    echo 'bar'
                } // withMaven will discover the generated Maven artifacts, JUnit Surefire & FailSafe reports and FindBugs reports}
            }
        }
    }
}

