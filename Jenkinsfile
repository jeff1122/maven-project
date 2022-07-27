pipeline{
	agent any
	stages{
		stage('step1'){
			steps{
				 bat '''  mvn clean package ''' 
			}
			post{
				success{
					echo 'start save file'
				}
			}
		}	
	}
}