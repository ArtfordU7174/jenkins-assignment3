pipeline {
    
    agent {
	label 'slave2'
	} 
	
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Sleep') {
            steps {
                sh 'sleep 120'
            }
        }
        
    }
}

