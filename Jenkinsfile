pipeline {
	 agent any 
	 
	 stages {
		stage("compile") {
			steps {
				echo "Compiling"
				bat """ javac HelloWorld.java """
				}
			}
			
		stage ("run") {
			steps {
				echo "Running"
				bat """ java HelloWorld"""
				}
			}
		}
	}