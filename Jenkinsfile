pipeline {
    agent any
    
    triggers {
         pollSCM('* * * * *') // Polling Source Control
     }

stages{
        
        stage ('Init'){
           echo "testing...."
        }

        stage('Build'){
            steps {
                echo "Building"
            }
        }
        
        stage ('Deployments'){
           echo 'Code deployed'
        }
    }
}