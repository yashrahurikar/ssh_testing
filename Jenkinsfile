#!groovy

node() {
    wrap([$class: 'AnsiColorBuildWrapper', 'colorMapName': 'XTerm', 'defaultFg': 1, 'defaultBg': 2]) {
    stages {
   stage('Build printenv'){
       steps {
           sh 'printenv'
       }
   }
}
}}
