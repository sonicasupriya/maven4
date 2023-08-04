@Library('mylib')_
pipeline
{
    agent any
    stages
    {
        stage('ContDownload_Loans')
        {
            steps
            {
                script
                {
                    cicd.gitDownload("maven")
                }
                
            }
        }
        stage('ContBuilt_Loans')
        {
            steps
            {
                script
                {
                    cicd.mavenBuild()
                }
               
            }
        }
}
}
