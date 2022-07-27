pipeline{
	agent any
	stages{
		stage('step1'){
			steps{
				"cmd /c mvn clean package  %$PATH% "
			}
			post{
				success{
					echo 'start save file'
				}
			}
		}	
	}
}