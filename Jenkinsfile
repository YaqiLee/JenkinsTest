pipeline {
  agent any

  def tag = "lyqhr2018/jenkinstest:latest"

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
                bat ("docker build -t ${tag} .")
                bat ("docker push ${tag}")
            }
        }
    }
}
