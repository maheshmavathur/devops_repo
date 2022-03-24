pipeline {
    agent any
    stages {
		stage ('Starting of the Stage') {
		parallel {
        stage('Stage 1') { 
            steps {
              sh "echo 'Hi'"
            }
        }
					stage('Stage 2') { 
					steps {
					sh "echo 'Good morning'"
					}
					}        
   
							stage('Stage 3') { 
								steps {
								  sh "echo 'OK Bye'"
								}
							}        
				}
			}
		}
	}
