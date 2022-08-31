pipeline
{
    agent any
    stages
    {
        stage ("Continous Download")
        {
            steps
            {
            git 'https://github.com/Padmanabham95/multi-pipeline.git'
            }                     
        }
        stage ("Continous Build")
        {
            steps
            {
            sh 'mvn package'
            }            
        }
    }
}

   
