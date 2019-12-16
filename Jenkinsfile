pipeline {
    agent any
    stages 
	{
        stage('build')
		{
            steps
			{
               bat '''Javac Student.java
			   java Student
				'''
            }
        }
    }
}