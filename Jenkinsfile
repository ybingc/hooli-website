pipeline {
    agent any

    options {
        // Stop the build early in case of compile or test failures
        skipStagesAfterUnstable()
    }

    stages {
        stage('Build') {
            steps {
                build 'build-bookzy'
            }
        }
        stage('Test') {
            steps {
                build 'test'
            }
        }
        stage('Deploy') {
            steps {
                build 'build-bookzy
            }
        }
    }
}
