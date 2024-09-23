pipeline {
    agent any

    stages {
        stage('git checkout'){
            steps{
                git branch: 'main', url: 'https://github.com/rombui/aws-cicd.git'
            }
        }
        stage('check'){
            steps{
                sh 'echo check'
            }
        }
    }


}