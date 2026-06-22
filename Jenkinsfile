pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/Miriam-code/Pipeline.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                echo 'Construction du projet...'
            }
        }
        stage('Test') {
            steps {
                echo 'Exécution des tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Déploiement de l’application...'
                sh 'ls -la'
            }
        }
    }
}
