pipeline {
    agent any 

    stages {
        stage ('build'){
        steps{
            sh 'pwd'
            sh 'ls -al'
        }}

        stage ('test'){
        steps{
            echo 'Test stage executed.'
        }}

        stage ('Deploy'){
        steps{
            echo 'Deployment stage executed.'
        }}


    }
}