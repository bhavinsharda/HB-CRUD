pipeline {
    agent { any }
    stages {
        stage('build') {
            steps {
		withMaven(maven : 'maven:3.1.1') {
				bat 'mvn --version'
			}
            }
        }
    }
}
