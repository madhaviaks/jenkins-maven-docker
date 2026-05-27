pipeline {
    agent any

    stages {

        stage('Build Maven Project') {
            steps {
                sh './mvnw clean package'
            }
        }

    }
}
