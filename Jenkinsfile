#!groovy

node {
    stage('Build') {
        sh 'echo Building'
        sh 'npm install package.json'
        sh 'npm run build'
    }
    stage('Test') {
        sh 'echo Testing'
    }
    stage('Deploy') {
        sh 'echo Deploying'
    }
}
