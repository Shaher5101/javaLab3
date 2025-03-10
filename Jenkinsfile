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
        stage('Run a Script') {
            steps {
                sh '''
                    echo "Running a custom script"
                    ./my-script.sh
                '''
            }
        }
    }
}
