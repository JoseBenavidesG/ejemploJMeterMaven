pipeline {
    agent any

    stages {
        stage('Performance') {
            steps {
                sh './mvnw.cmd verify -Pperformance'
            }
        }
    }
}
