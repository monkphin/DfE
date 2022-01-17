pipeline {
    agent any 

    stages {
        stage ('build'){
        steps{
            sh 'pwd'
            sh 'ls -al'
            sh cp * -r ~/Documents/MultiBranchPipeline-Job
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