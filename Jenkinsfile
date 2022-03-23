pipeline {
    agent any
    stages {
        stage ('Build application') {
            steps {
                sh 'docker build -t ubuntu_python .'
               
            }
        }
    }
}