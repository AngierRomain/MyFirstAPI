pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'curl https://127.0.0.1:8081/blog/'
            }
        }
    }
}
