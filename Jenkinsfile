pipeline {
	agent any
	
	stages {
		stage ('Compile Stage') {
	
			steps{
			   withMaven(maven : 'Maven 3.1.1') {
				sh 'mvn compile'
			}
		    }
		}
		stage ('Testing Stage') {
	
			steps{
			   withMaven(maven : 'Maven 3.1.1'){
				sh 'mvn test'
			}
		    }
		}
		stage ('Deployment Stage') {
	
			steps{
			   withMaven(maven : 'Maven 3.1.1') {
				sh 'mvn deploy'
			}
		    }
		}		
           }
       }
