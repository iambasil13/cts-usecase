@Library('Shared-library@master') _

pipeline {
  agent any 

    stages {
	
		stage('Checkout') {
			steps {
			 gitclone(
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
