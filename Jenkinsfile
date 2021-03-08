pipeline{
agent any
	environment
	{
		jenkins= "Jenkins outside "
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

		stage('Parallel in Secuential'){
			parallel {
				stage('In parallel 1'){
					steps{
						echo "In parallel 1"
					}
				}
				stage('In parallel 2'){
					steps{
						echo "In parallel 2"
					}
				}
			}
		}

	}
}