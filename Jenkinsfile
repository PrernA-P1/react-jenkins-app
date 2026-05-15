pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git 'https://github.com/PrernA-P1/react-jenkins-app.git'
            }
        }

        stage('Install') {
            steps {
                bat 'npm install'
            }
        }

        stage('Build') {
            steps {
                bat 'npm run build'
            }
        }
    }
}