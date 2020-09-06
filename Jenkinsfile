pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('check java version') {
            steps {
                bat 'java -version'
            }
        }
    }
}
