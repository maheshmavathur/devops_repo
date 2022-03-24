pipeline {
    agent any
    stages {
        stage('Stage 1') 
		{ 
            steps 
			{
			parallel
			(
				stage1: {
              sh "echo "Hi, Good Morning!!""
			  },
			  
			  stage2: {
              sh "echo "This is a test branch!!""
			  }
			  
			  stage3: {
              sh "echo "OK, TESTED""
			  }
			)
            }
		}

        }        
    }
