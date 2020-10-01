pipeline {
agent any
stage('SCM Checkout'){
//git 'https://github.com/vkchellaturu/welcometoskillrary.git'
git credentialsId: 'GIT_HUB_REPO', url: 'https://github.com/vkchellaturu/welcometoskillrary'
}
stage('Compile-package'){
 sh "mvn package"
}
}
