pipeline {
    agent any

    stages {
        
        stage('Clone Repo') {
            steps {
                script{
                    git 'https://github.com/kozi2712/DevOps.git'
			        echo 'The repository was successfully cloned.'
                }

            }
        }
        stage('Build') {
            steps {
                script{
			        echo 'Stage build'
                }

            }
        }
        stage('Test') {
            steps {
                script{
			        echo 'Stage Test'
                }

            }
        } 
        stage('Deploy') {
            steps {
                script{
			        echo 'Stage deploy'
                }

            }
            
            
        }
    }
}
