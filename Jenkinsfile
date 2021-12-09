pipeline {
    agent any
    
    stages{
        stage("Echo name")
        {
            steps {
                script {
                    echo "MY NAME IS SHIVAM"
                }
            }
        }
    }
    
    post {
        success {
            echo 'Build is Successfull'
        }
        
        failure {
            echo 'Build is Failed'
        }
    }
}
