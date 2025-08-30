// Jenkinsfile

pipeline {
    agent any

    stages {
        stage('Clonar o repositório') {
            steps {
                git branch: 'main', url: 'https://github.com/ebac-qe/ebac-cypress-samples.git'
            }
        }

        stage('Instalar dependencias') {
            steps {
                sh 'npm install'
            }
        }

        stage('Executar Testes') {
            steps {

                sh 'NO_COLOR=1 npm run cy:run'
            }
        }
    }
}