pipeline{
    agent any
    stages{
        stage('git'){
            steps{
                git credentialsId: 'githup_creds', url: 'https://github.com/abinaya-s2006/pipelinescm.git'
             }
        }
        stage('build'){
            steps{
                echo "python start"
                sh 'python --version'
            }
        }
        stage('test'){
            steps{
                echo "python processing"
                sh 'jenkins --version'
            }
        }
        stage('deploy'){
            steps{
                echo "python running"
                sh 'python3 app.py'
            }
        }
    }
}
