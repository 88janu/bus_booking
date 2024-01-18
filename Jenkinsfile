pipeline {
    agent {label 'slave1'}
    stages {
        stage('checkout') {
            steps {
                sh 'rm -rf '
                sh 'git clone '
            }
        }
        stage('build') {
            steps {
                sh 'mvn --version'
                sh 'mvn clean install'
            }
        }
        stage('deploy') {
            steps {
                
                
        }
    }
}
