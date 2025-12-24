pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Build"
			}
		}
		stage('Test') {
			steps {
				echo "Test"
			}	
		}
		stage('Integration') {
			steps{
				echo "Integration"
			}
		}
	}
	post {
		always{
			echo"I runinng always"
			}
	success{
		echo"I run you when you successed"
		}
	failure{
		echo"I runinng when you failed"
		}
	}
}
