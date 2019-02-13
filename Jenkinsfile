pipeline { 
    
    agent any 
    
    stages { 
        
        stage('Example clean') {
            steps { 
                sh "mvn clean " 
            } 
            
        } 

        stage('Example install') { 
            steps { 
                sh "mvn install" 
            }
        }

        stage('Example test') { 
            steps { 
                sh "mvn test" 
            }        
        } 
        
        stage('Example package') {
            steps { 
                sh "mvn package" 
            }
        }
    }  
}
