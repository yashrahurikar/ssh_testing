#!groovy

node {
    stage('Build') {
        sh 'echo Building'
        sh 'yarn add package.json'
        sh 'yarn start'
    }
    stage('Test') {
        sh 'echo Testing'
    }
    stage('Deploy') {
        sh 'echo Deploying'
    }
}
