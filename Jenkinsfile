// Jenkinsfile 

pipeline {
    agent any

    stages {
        stage('Instalar dependencias') {
            steps {
                bat 'npm install'
            }
        }

        stage('Executar Testes') {
            environment {
                NO_COLOR = '1'
            }
            steps {
                bat 'npm run test'
            }
        }
    }
}}