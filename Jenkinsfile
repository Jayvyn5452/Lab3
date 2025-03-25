pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/your-username/your-repo.git'
            }
        }

        stage('Build Java Project') {
            steps {
                sh 'javac Main.java'
            }
        }
    }
}