pipeline {
    agent any
    
    triggers {
        cron('H H * * *')
    }
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
                build 'test-bookzy'
            }
        }
        stage('Deploy') {
            steps {
                build 'build-bookzy'
            }
        }
    }
}
