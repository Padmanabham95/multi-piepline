pipeline
{
    agent any
    stages
    {
        stage ("Continous Download")
        {
            git 'https://github.com/Padmanabham95/multi-pipeline.git'  
        }
        stage ("Continous Build")
        {
            sh 'mvn package'
        }
    }
}

   
