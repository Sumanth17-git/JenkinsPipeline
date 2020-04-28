pipeline
{
    agent any
    stages
    {
        stage("SCM Checkout")
        {
            steps{
                //Get source code from GitHub repository
                git credentialsId:'GitHub', url:'https://github.com/Sumanth17-git/war-web-projects.git'
            }
        }
        stage("Build")
        {
            steps{
                sh 'mvn clean deploy'
            }
        
        }
   }
}
