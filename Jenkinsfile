pipeline {
    agent any

    stages {
        
        stage('Clone Repo') {
            steps {
                script{
                    checkout([$class: 'GitSCM', 
                    branches: [[name: '*/main']], 
                    userRemoteConfigs: [[url: 'https://github.com/kozi2712/DevOps']]])
            		
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
