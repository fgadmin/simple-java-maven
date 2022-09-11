pipeline {
    agent any  
    stages {
        stage('Build') {
            steps {
                sh 'mvn -Dmaven.test.failue clean package'
            }
        }
    }
}
