pipeline{
agent any
	environment
	{
		jenkins= "Jenkins outside "
	}
	parameters
	{
		string {name: "Person", defaultValue: "JenkinsMSR", description: "Ser your name"}
	}
	stages{
		stage('Start'){
			input{
				message "Deply to production"
				ok "yes, Deploy"
				submitter "estradahugo01032021"
			}
			steps{
				echo "Hello"
				echo "test"
			}
		}

		stage('Build'){
			steps{
				echo "Second Step " + jenkins
			}
		}		
	}
}