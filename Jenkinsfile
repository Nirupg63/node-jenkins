pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat "npm install"
            }
        }
         stage('test') {
            steps {
                bat "npm test"
            }
        }
        stage('deploy') {
            steps {
                echo "Code is being deployed"
            }
        }
    }
}