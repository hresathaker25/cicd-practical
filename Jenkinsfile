pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                echo 'Cloning from GitHub...'
            }
        }
        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }
        stage('Deploy') {
            steps {
                bat 'copy index.html C:\\Users\\YourName\\deploy\\'
            }
        }
    }
}