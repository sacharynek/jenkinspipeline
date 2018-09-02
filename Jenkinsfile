pipeline {
    agent any
    
    triggers {
         pollSCM('* * * * *') // Polling Source Control
     }

stages{
        
        stage ('Init'){
            steps {
           bat "powershell.exe echo testing...."
            }
        }

        stage('Build'){
            steps {
            bat "powershell.exe echo Building"
            }
        }

        stage ('Deployments'){
            steps {
           bat "powershell.exe echo Code deployed"
            }
        }
    }
}