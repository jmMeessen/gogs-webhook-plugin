pipeline {
    agent none

    stages {
        stage('Build') {
            agent { label 'docker' }
            steps {
                echo 'Building..'
            }
        }
        stage('Integration tests') {
            agent any
            steps {
                echo 'Testing..'
            }
        }
    }
}