pipeline {
    agent any
    
    tools {nodejs "node"} 
    
    stages {
        stage('Build') {
            steps {
                
                echo 'hello'
            }
        }
    }
}

