pipeline
 {
agent any 
    stages {
        stage('Fetch') { 
            steps {
                git url:'https://github.com/brendanmitchell1/jenkins_project'
            }
        }
    stages
	{
        stage('Build')
		{
            steps
			{
               bat  "javac Student.java"
			   
            }
       
		}
		stage('Test')
		{ 
            steps
			{
                bat '''
                java -cp junit-4.12.jar;hamcrest-core-1.3.jar;. org.junit.runner.JUnitCore studentTest
                '''
                
                
            }
		}
	}
}