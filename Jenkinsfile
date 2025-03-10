pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello, this is a Jenkins job without Maven!'
            }
        }
        stage('List Files') {
            steps {
                sh 'ls -la' // List files in the workspace
            }
        }
        // Remove or replace the "Run a Script" stage
        stage('Run a Script') {
            steps {
                echo 'Skipping script execution because my-script.sh is not found.'
            }
        }
    }
}
