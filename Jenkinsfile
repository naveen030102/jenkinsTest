pipeline
{
agent any
    stages
    {
        stage("FIRST STAGE")
        {
         steps
            {
                echo "step one success ------0-0-0-0---------"
            }
        }
        
        stage("pulling from git")
        {
            steps
            {
           sh """
           python pyfile.py
           """
            }
        }
    }
}
