pipeline{
    agent any
    
    stages{
        stage('Build'){
            steps{
                echo 'Building...'
                sleep 5
            }
        }
                stage('Static code analysis'){
            steps{
                echo 'Static code analysis...'
                sleep 5
            }
        }
                stage('Test'){
            steps{
                echo 'Testing...'
                exit 1
            }
        }
                stage('Deploy'){
            steps{
                echo 'Deploying...'
                sleep 5
            }
        }
    }
}
