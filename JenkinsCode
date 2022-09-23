pipeline {
    agent any
    
    stages {
        stage('Build') 
        {
            steps 
            {
                echo 'Build Code'
            }
        }
         stage('Test') 
        {
            steps 
            {
                echo 'Test Code'
            }
        }
         stage('Deploy') 
        {
            steps 
            {
                echo 'Deploy Code'
            }
        }
    }
    post
    {
        always
        {
            emailext body: 'Email Alert from Jenkins', subject: 'Assignment', to: 'vasukumarsingh8143@gmail.com'
        }
    }
}
