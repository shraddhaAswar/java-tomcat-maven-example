pipeline {
    agent any
    tools {
        any
    }
    stages {
        stage ('Cloning the repository') {
            steps {
                sh '''
                    echo "Cloning the rpo"
                '''
				}
		}
		stage ('Maven Build') {	
			steps {
                sh '''
                    echo "Maven Build"
                '''
				}
		}			
		stage ('Maven Test') {	
			steps {
                sh '''
                    echo "Maven test"
                '''
				}
		}
		stage ('Deploy') {	
				steps {
                sh '''
                    echo "Deploy"
                '''
				}
        }
}
}

