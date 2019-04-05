pipeline
{
    agent any
    stages
    {
      stage ("fetching code")
      {
        steps
        {
          git 'https://github.com/VTfreshers/jenkins_demo.git'
        }
      }
      stage ("building")
      {
        steps
        {
            sh './gcc_shell.sh'
        }
      }
    }
}
