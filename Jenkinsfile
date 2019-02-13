pipeline { 
    
    agent any 
    
    stages { 
        
        stage('Example clean') {
            steps { 
                sh "/usr/local/src/apache-maven/bin/mvn clean kouami-app" 
            } 
            
        } 

        stage('Example install') { 
            steps { 
                sh "/usr/local/src/apache-maven/bin/mvn install kouami-app" 
            }
        }

        stage('Example test') { 
            steps { 
                sh "/usr/local/src/apache-maven/bin/mvn test kouami-app" 
            }        
        } 
        
        stage('Example package') {
            steps { 
                sh "/usr/local/src/apache-maven/bin/mvn package kouami-app" 
            }
        }
    }  
}
