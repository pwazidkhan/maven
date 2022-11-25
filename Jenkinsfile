@Library('mylibrary')_

node('built-in')
{
    stage('ContDownload')
    {
        cicd.newDownload("maven.git")
    }
    stage('ContBuild')
    {
        cicd.newBuild()
    }
    
}  
       
