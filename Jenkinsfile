pipeline 
{
    agent any
    stages 
    {
        stage('Build') 
        {
            steps 
            {
                sh 'echo "ls:..."'
                sh 'ls'

                sh 'echo "Building... chmod"'
                sh 'chmod +x LinuxBuild.sh'

                sh 'echo "Building... LinuxBuild"'
                sh 'LinuxBuild.sh'
                
                sh 'echo "Building... Built"'
            }
        }
    }
}
