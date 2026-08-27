pipeline{
    agent any
    stages{
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
