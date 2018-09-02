pipeline {
    agent any
    
    triggers {
         pollSCM('* * * * *') // Polling Source Control
     }

stages{
        
        stage ('Init'){
           powershell "echo testing...."
        }

        stage('Build'){
            
            powershell "echo Building"
            
        }

        stage ('Deployments'){
           powershell 'echo Code deployed'
        }
    }
}