pipeline {
    agent any
    
    tools {
        maven 'apache-maven-3.0.1' 
    }

    stages {
        stage('check maven version') {
            steps {
                bat 'mvn --version'
            }
        }
        
        stage('check java version') {
            steps {
                bat 'java -version'
            }
        }
        
        stage('check golang environment') {
            steps {
                bat 'go env'
            }
        }
    }
}
