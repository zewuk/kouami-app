pipeline { 
    
    agent any 
    
    stages { 
        
        stage('Example clean') {
            steps { 
                sh "mvn clean kouami-app" 
            } 
            
        } 

        stage('Example install') { 
            steps { 
                sh "mvn install kouami-app" 
            }
        }

        stage('Example test') { 
            steps { 
                sh "mvn test kouami-app" 
            }        
        } 
        
        stage('Example package') {
            steps { 
                sh mvn package kouami-app" 
            }
        }
    }  
}
