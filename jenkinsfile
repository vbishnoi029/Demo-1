pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'code build'
            }
        }
        stage('test') {
            steps {
                echo 'code test'
                sh 'ls'
                sh 'sleep 15'
            }
        }
        stage('deploy') {
            steps {
                echo 'code deploy'
                sh 'sleep 30'
            }
        }
    }

}
