pipline {
	agent any
	stages('Build'){
		steps{
			echo "Build"
		}
	}
	stages('Test'){
		steps{
			echo "Test"
		}
	}
	stages('Integration'){
		steps{
			echo "Integration"
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
