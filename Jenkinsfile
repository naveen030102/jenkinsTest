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
        
        stage("running python file")
        {
            steps
            {
           sh """
           ls
           python pyfile.py
           """
            }
        }
        
        
         stage("sh file testng")
        {
            steps
            {
           sh """
           ls
           ./run.sh
           """
            }
        }
    }
}
