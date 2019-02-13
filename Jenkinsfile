pipeline { 
    
    agent any 
    
    stages { 
        
        stage('Example clean') {
            steps { 
                sh "/usr/local/src/apache-maven/bin/mvn clean -f kouami-app" 
            } 
            
        } 

        stage('Example install') { 
            steps { 
                sh "/usr/local/src/apache-maven/bin/mvn install -f kouami-app" 
            }
        }

        stage('Example test') { 
            steps { 
                sh "/usr/local/src/apache-maven/bin/mvn test -f kouami-app" 
            }        
        } 
        
        stage('Example package') {
            steps { 
                sh "/usr/local/src/apache-maven/bin/mvn package -f kouami-app" 
            }
        }
    }  
}
