pipeline {
    agent any
    
    

    
        
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
