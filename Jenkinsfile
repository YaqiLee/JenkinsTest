pipeline {
  agent any
  stages {
        // stage('Build') {
        //     steps {
        //         bat 'npm --version'
        //         bat 'npm install'
        //         bat 'npm start'
        //     }
        // }
        stage('Docker build') {
            steps {
                bat docker build -t lyqhr2018/jenkinstest .
                bat docker push lyqhr2018:jenkinstest
            }
        }
    }
}
