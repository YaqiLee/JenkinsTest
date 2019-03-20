node {
    def nodeHome = tool 'NodeJS_8.12'
     stage('Build') {
        withEnv(["PATH+NODE=${ nodeHome }/bin"]) {
            sh "npm config set registry='http://192.168.11.20:8081/repository/npm-all/'"
            sh 'rm -rf node_modules'
            sh 'npm install'
        }
    }
}