pipeline {
    agent { label 'master' }
    stages {
        stage('git'){
            steps{
                sh 'git clone https://github.com/akash1994sarkar/cp4a-install.git'
            }
        }
        stage('build') {
            steps {
                sh "cd cp4a-install"
                sh "./cp4a-install.sh"
            }
        }
    }
}
