@Library('mylibrary')_
pipeline
{
    agent any
    stages
    {
        stage('ContDownload')
        {
            steps
            {
                script
                {
                    cicd.newDownload("maven.git")
                }
            }
        }
        stage('ContBuild')
        {
            steps
            {
                script
                {
                    cicd.newBuild()
                }
            }
        }
       

   }
}
