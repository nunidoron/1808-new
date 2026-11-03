properties([pipelineTriggers([pollSCM('H * * * *')])])
pipeline{
    agent any
    stages{ 
        stage("execute python"){
            steps{
                sh "python3 main.py"
            }
        }
    }
}
