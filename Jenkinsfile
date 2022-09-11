pipeline {
    agent any  
    
	tools {
	  maven "MAVEN"
	  }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -Dmaven.test.failue clean package'
            }
        }
    }
}
