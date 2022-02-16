pipeline {
    agent any

    stages {
        stage ('Build Image') {
            steps {
                script {
                    dockerapp = docker.build("jenniedocker/api-produto:", '-f ./src/Dockerfile ./src') 
                }                
            }
        }
