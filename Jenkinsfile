pipeline {
    agent any

    stages {
        stage ('Build Image') {
            steps {
                script {
                    dockerapp = docker.build("jenniedocker/api_produto", '-f ./src/Dockerfile ./src')
                }
                
            }
        }
    }
}