pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'docker ps'
            }
        }
        stage('test') {
            steps {
                echo 'Test stage is being executed'
            }
        }
        stage('deploy') {
            steps{
                echo 'Deploy stage is being executed'
            }
        }
    }
}
