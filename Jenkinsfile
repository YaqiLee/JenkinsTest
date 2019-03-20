
pipeline {
   agent {
    node {
        stages {
            stage('build') {
                steps {
                    bat 'npm --version'
                    bat 'npm install'
                    bat 'npm start'
                }
            }
        }
    }
  }
}
