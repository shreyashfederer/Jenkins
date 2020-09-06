pipeline {
    agent any
    
    environment {
        
        OperatingSYstem = 'Windows'
        name = 'Shreyash'
    
    }
    stages {
        
        stage('Print environment variables') {
            steps {
                echo 'Hello World'
                bat 'java -version'
                bat 'set'
                echo '$OperatingSYstem'
            }
        }
        
        
        stage('Example Build') {
            steps {
                echo 'Hello World'
                bat 'java -version'
            }
        }
        stage('Example Deploy') {
            when {
                branch 'production'
            }
            steps {
                echo 'Deploying'
                bat 'go env'
            }
        }
    }
}
