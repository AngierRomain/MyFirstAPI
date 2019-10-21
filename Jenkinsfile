pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'curl http://127.0.0.1:8081/blog/ -UseBasicParsing'
            }
        }
    }
}
