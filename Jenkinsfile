pipeline 
{
    agent any

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'Build App new one'
            }
        }

        stage('Test') 
        {
            steps 
            {
                echo 'Test App new 2'
            }
        }

        stage('Deploy') 
        {
            steps 
            {
                echo 'Deploy App new three'
            }
        }
    }

    post
    {

    	always
    	{
    		emailext body: 'Summary', subject: 'Pipeline Status', to: 'selenium3bymukesh@gmail.com'
    	}

    }
}
