pipeline{
	agent any
	stages{
	  stage{
		steps{
		  echo 'Running the build automation'
		  sh './gradlew build --no-deamon'
		  archiveArtifacts artifacts: 'dist/trainSchedule.zip'
}
}
}
}
