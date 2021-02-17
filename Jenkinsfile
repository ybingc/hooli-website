pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                build 'build-bookzy'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
