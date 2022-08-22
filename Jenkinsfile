pipeline {
    agent any
    stages {
        stage('Install') {
            steps {
                withMaven {
                    sh 'mvn clean verify'
        } // withMaven will discover the generated Maven artifacts, JUnit Surefire & FailSafe reports and FindBugs reports}
            }
        }
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

