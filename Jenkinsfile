pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh '''ls 
date'''
      }
    }

    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'hello word'
          }
        }

        stage('validate') {
          steps {
            sh 'cal 2025'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        sleep 30
      }
    }

  }
}