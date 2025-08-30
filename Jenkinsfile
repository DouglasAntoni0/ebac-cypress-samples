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
            steps {
                bat 'NO_COLOR=1 npm run cy:run'
            }
        }
    }
}