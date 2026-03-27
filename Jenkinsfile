@Library('mylibrary')_

node('built-in')
{
    stage('ContDownload')
    {
        cicd.newDownload("maven3.git")
    }
    stage('ContBuild')
    {
        cicd.newBuild()
    }
    
}
