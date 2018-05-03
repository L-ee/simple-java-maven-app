pipeline {
	agent {
		docker {
			image 'docker.io/maven:latest'
		}
	}
	stages {
	   stage('Build'){
		steps {
			sh 'mvn -v'
		}		
	   }
	}
}
