node {
	stage ('get code')
	{
	checkout scm
	}
	stage('clean the project')
	{
	sh 'mvn clean'
	}
	
	stage ('Test')
	{
	sh 'mvn test'
	}

}
