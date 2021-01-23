pipeline {
    agent any

    stages {
        stage('Performance') {
            steps {
                sh 'mvn verify -Pperformance'
            }
        }
    }
}
