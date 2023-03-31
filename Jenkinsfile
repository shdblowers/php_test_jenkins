pipeline {
    agent { docker { image 'php:8.2-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}
