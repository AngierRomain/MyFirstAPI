pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'curl http://localhost:8080/blog/'
            }
        }
    }
}
