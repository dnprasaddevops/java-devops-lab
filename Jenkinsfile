pipeline {
	agent any
		
	stages {
		stage('Build'){
			steps {
				sh "javac Hello.java"
			}
		
		}

		stage('Package'){
		     steps {

			sh "jar cfe hello-executable.jar Hello Hello.class"

			}
		}

	}

}
