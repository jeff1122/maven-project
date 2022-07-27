pipeline{
	agent any
	stages{
		stage('step1'){
			steps{
				echo 'cmd /c mvn clean package $PATH ,  ' %$PATH%
			}
			post{
				success{
					echo 'start save file'
				}
			}
		}	
	}
}