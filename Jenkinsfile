pipeline{
	agent any
	stages{
		stage('step1'){
			steps{
				sh 'mvn clean package'
			}
			post{
				success{
					echo 'start save file'
				}
			}
		}	
	}
}