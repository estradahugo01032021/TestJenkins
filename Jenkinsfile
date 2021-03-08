pipeline{
agent any
	environment
	{
		jenkins= "Jenkins outside "
	}
	stages{
		stage('Start'){
			steps{
				echo "Hello"
				echo "test"
				}
		stage('Build'){
			steps{
				echo "Second Step"	 + jenkins
			}
		}	
		}
	
}
