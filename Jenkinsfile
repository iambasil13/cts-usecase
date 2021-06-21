@Library('shared-library') _

pipeline {
  agent any 

    stages {
	
		stage('Checkout') {
			steps {
			 git(
				branch: "master",
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
