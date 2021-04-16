pipeline {
    tools {
        maven 'maven 3.6'
        }    
    agent any 
    stages {
        stage('Clean') { 
            steps {
                bat "mvn clean"
            }
        }
        stage('Test') { 
            steps {
                bat "mvn test"
            }
        }
        stage('Package') { 
            steps {
                bat "mvn package" 
            }
        }
    }
}
