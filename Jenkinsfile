pipeline {
    agent any
    
    

    
        
        stage('check java version') {
          
            when {
             
                branch 'master'
            }  
               
                
                
            
            
              steps {
                   bat 'java -version'
                echo "I am in when"
                bat 'java -version'
            }
            
            steps {
                echo "I am not in in when"
            }
        }
        
        stage('check golang environment') {
            steps {
                bat 'go env'
            }
        }  
    
}
