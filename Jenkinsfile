pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                withMaven {
                    sh 'mvn clean verify'
                    echo 'foobar'
        } // withMaven will discover the generated Maven artifacts, JUnit Surefire & FailSafe reports and FindBugs reports}
            }
        }
    }
}

