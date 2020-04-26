pipeline
{
    agent any
    stages
    {
        stage("SCM Checkout")
        {
            steps{
                //Get source code from GitHub repository
                git credentialsId:'GitHub', url:'https://github.com/Sumanth17-git/Project1.git'
            }
        }
        stage("Build")
        {
            steps{
                sh 'mvn install'
            }
        
        }
   }
}
