  
pipeline {
    agent any
    options {
        lock(label: 'win', quantity: 1)
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Branch2!"'
                sleep 60
            }
        }
    }
}
