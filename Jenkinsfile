pipeline {
    agent any
    stages {
        stage('Parallel 1') {
            parallel {
                stage('Parallel run 1') {
                    steps {
                        sh "echo "Hi, Good morning!!""
                    }
                }
                stage('Parallel run 2') {
                    steps {
                       sh "echo "How are you?""
                        
                    }
                }
            }
        }
    }
}
