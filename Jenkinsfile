pipeline{
    agent {
        label 'slave' 
    }

    stages{
        stage('hostname'){
            steps{
                sh "hostname"
            }
        }
        stage('Server Ip address'){
            steps{
                sh "hostname -I"
            }
        }
        stage('disc usage'){
            steps{
                sh "df -h"
            }
        }
        stage('Server uptime'){
            steps{
                sh "uptime"
            }
        }
        stage('memory usage'){
            steps{
                sh "free -h"
            }
        }
    }
}
