pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'curl 127.0.0.1:8080/blog/'
            }
        }
    }
}