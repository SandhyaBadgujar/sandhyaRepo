pipeline{
    agent{
        label 'master'
    }
    stages{
        
        stage ("getting hostname"){
            steps{
                
                sh (script:'hostname')
            }
        }
        stage ("getting date"){
            steps{
                sh (script :'date')
            }
            
            
        }
    }
    
}
