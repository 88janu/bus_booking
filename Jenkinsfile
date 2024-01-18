pipeline {
    agent {label 'slave1'}
    stages {
        stage('checkout') {
            steps {
                sh 'rm -rf bus_booking'
                sh 'git clone https://github.com/88janu/bus_booking.git'
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
                sh 'echo "deploying"'
            }
                
        }
    }
}
