
pipeline {
  agent any
  stages {
        stage('Build') {
            steps {
                bat 'npm --version'
                bat 'npm install'
                bat 'npm start'
            }
        }
    }
}
