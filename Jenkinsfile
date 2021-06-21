@Library('shared-library') _

pipeline {
  agent any 
		tools {
		jdk 'JAVA'
		git 'Default'
	}
    stages {
	
		stage('Checkout') {
			steps {
			 git(
				branch: "main",
				url: "https://github.com/iambasil13/cts-usecase.git"
				)
			}
		}
		
		stage('Analyze&Report') {
			steps {
			 //Test()
			InputCSV()
			//CSVrun()
			}
		}	
		
	}
	
}
