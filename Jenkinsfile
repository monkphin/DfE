pipeline {
    agent any 

    stages {
        stage ('build'){
        steps{
            echo 'Build stage executed.' 
            sh 'docker-compose -f /var/lib/jenkins/workspace/MultiBranchPipeline-Job_main/webapp/docker-compose.yml up --build -d'

        }}

        stage ('test'){
        steps{
            echo 'Test stage executed.'
            echo 'microservices stopped'
            sh 'docker-compose down'
            sh 'docker rm $(docker ps -aq)'
        }}

        stage ('Deploy'){
        steps{
            echo 'Deployment stage executed.'
        }}

        stage ('Post Check'){
        steps{
            echo 'Post Checks stage executed.'
        }}

    }
}