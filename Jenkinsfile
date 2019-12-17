pipeline{
	agent any
	stages{
		stage('Build'){
			steps{
			    echo "Build"
			}			
		}
		stage('Test'){
			steps{
				echo "Test"
			}			
		}
		stage('Deploy'){
			steps{
				echo "Deploy"
				sh "echo \"Build ID: ${env.BUILD_ID}, Jenkins URL: ${env.JENKINS_URL}\" >> EnvFile"
			}			
		}
	}
}
