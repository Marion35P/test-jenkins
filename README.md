pipeline {
    agent any

    stages {
        stage('STARTING') {
            steps {
                echo 'starting stage 1'
            }
        }
        stage('BUILD') {
            steps {
                echo 'build stage 2'
            }
        }
        stage('DEPLOY') {
            steps {
                echo 'deploy stage 3'
            }
        }
    }
}
