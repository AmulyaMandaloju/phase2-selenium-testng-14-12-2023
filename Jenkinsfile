pipeline {

	agent any
	
	triggers {
		pollSCM('* * * * *')
	}
	
	stages {
		
		stage('Compile stage') {
			steps {
				echo '--------------:: This is a compile stage :: ------------'
				bat 'mvn clean compile'
			}
	
		}
		
		
	}

}