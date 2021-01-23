pipeline {
    agent any

    stages {
        stage('Performance') {
            steps {
               mvn verify -Pperformance
            }
        }
    }
}
