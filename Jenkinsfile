node{
  stage('SCM Checkout') {
    git 'https://github.com/Arun8055643220/facebook-project'
    }
     stage('Complie-package'){
        def mvnHome =tool name: 'mavan', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
        }
        }
