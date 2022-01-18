pipeline {
    agent any 

    stages {
        stage ('build'){
        steps{
            sh 'pwd'
            sh 'ls -al'
            sh 'mkdir /home/darren/Documents/MultiBranchPipeline-Job'
            sh 'cp -r /var/lib/jenkins/workspace/MultiBranchPipeline-Job_main /home/darren/Documents/MultiBranchPipeline-Job'
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