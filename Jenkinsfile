pipeline
 {
    agent any

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
                bat '''javac -cp junit-4.12.jar;studentTest.java 
                java -cp junit-4.12.jar;hamcrest-core-1.3.jar;. org.junit.runner.JUnitCore studentTest
                '''
                
                '''
            }
		}
	}
}