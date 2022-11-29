pipeline{
    
    agent any 
    
    stages {
        
        stage('Git Checkout'){
            
            steps{
                
                script{
                    
                    git branch: 'main', url: 'https://github.com/ankushc123/demo-counter-app.git'
                }
            }
        }    
        stage('maven test'){
            
            steps{
                
                script{
                    
                   sh 'mvn test'
                }
            }
        }       
}
}
                    
                    
