pipeline {
    agent any 

    stages {
        stage ('build'){
        steps{
            sh 'cd /var/lib/jenkins/workspace/MultiBranchPipeline-Job_main/webapp'
            sh 'docker-compose - f /var/lib/jenkins/workspace/MultiBranchPipeline-Job_main/webapp/docker-compose.yml --build'
        }}

        stage ('test'){
        steps{
            echo 'Test stage executed.'
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