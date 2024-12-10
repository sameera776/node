pipeline
{
    agent any
    stages
    {
        stage("build")
        {
            steps
            {
                bat "docker build -t node ."
            }
        }
        stage("Runing tests")
        {
            steps
            {
                echo "Running tests"
            }
        }
        stage("Deploy")
        {
            steps
            {
                echo "Deploy tests"
            }
        }
    }
}