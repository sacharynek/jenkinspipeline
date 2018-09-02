pipeline {
    agent any
    
    triggers {
         pollSCM('* * * * *') // Polling Source Control
     }

stages{
        
        stage ('Init'){
           bat "powershell.exe echo testing...."
        }

        stage('Build'){
            
            bat "powershell.exe echo Building"
            
        }

        stage ('Deployments'){
           bat "powershell.exe echo Code deployed"
        }
    }
}