pipeline {
    agent any 
    stages {
        stage('SCM Checkout') { 
            steps {
                git credentialsId: 'GIT_HUB_REPO', url: 'https://github.com/vkchellaturu/welcometoskillrary'
            }
        }
        stage('Compile-package') { 
            steps {
                 sh "mvn package"
            }
        }
    }
}
