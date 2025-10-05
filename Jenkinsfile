@Library('jenkins-shared-lib-demo') _

pipeline {
    agent any

    stages {
        stage('Init') {
            steps {
                echo "Starting Jenkins Shared Library Demo..."
            }
        }

        stage('Use Shared Library') {
            steps {
                // This calls vars/hello.groovy -> def call()
                hello()
            }
        }

        stage('Complete') {
            steps {
                echo "Pipeline completed successfully!"
            }
        }
    }
}
