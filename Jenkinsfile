pipeline {
    agent any

    stages {
        stage('Performance') {
            steps {
                if (isUnix()) { /* Linux / OSX */
                    sh './mvnw verify -Pperformance'
                } else { /* Windows */
                    sh './mvnw.cmd verify -Pperformance'
                }
            }
        }
    }
}
