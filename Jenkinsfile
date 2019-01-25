#!groovy

node {
    stage('Build') {
        sh 'echo Building'
        sh 'npm installpackage.json'
        sh 'npm run build'
    }
    stage('Test') {
        sh 'echo Testing'
    }
    stage('Deploy') {
        sh 'echo Deploying'
    }
}
