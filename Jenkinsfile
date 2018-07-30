pipeline {
    agent { docker 'maven:3.1.1' }
    stages {
        stage('build') {
            steps {
                bat 'mvn --version'
            }
        }
    }
}
