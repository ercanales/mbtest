  
pipeline {
    agent any
    options {
        lock(label: 'win', quantity: 1)
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello world!"'
            }
        }
    }
}
