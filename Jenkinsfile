pipeline{
	agent any
	stages{
		stage('step1'){
			steps{
				echo 'mvn clean package'
			}
			post{
				success{
					echo 'start save file'
				}
			}
		}	
	}
}