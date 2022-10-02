pipeline {
	agent any 
	stages{
		stage('Main branch Deploy Code'){
			when {
				branch 'main'
			}
			steps{
				sh 'echo "Building artifact from Main branch"'
				sh 'echo "Deploying code from Main branch"'
			}
		}
		stage('Develop Branch Deploy Code'){
			when {
				branch 'develop'
			}
			steps{
				sh 'echo "Building artifacts from develop branch"'
				sh 'echo "Deploying code from Develop branch"'
			}
		}
	}
}
