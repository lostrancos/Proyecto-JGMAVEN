pipeline {
    
    agent any
    
    stages {
         
        stage("Etapa1") {
            steps{
                sh "echo Soy la etapa 1"
            }
         
          stage("Etapa2") {
            steps{
                sh """
                echo Soy la etapa 2
                echo Soy otra vez la etapa 2
                """
            }
         
         }
     }
}