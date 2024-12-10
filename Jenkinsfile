pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repository...'
                git branch: 'main', url: 'https://github.com/AlexYess/JNKS_repo.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'echo Build successful!'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo Tests passed!'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                sh 'echo Deployment successful!'
            }
        }
    }
}
