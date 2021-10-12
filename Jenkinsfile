pipeline {
    agent any

    environment {
        secret = credentials('SECRET_TEST')
    }
    stages {
        stage('Example stage 1') {
            steps {
                sh 'echo $secret'
            }
        }
    }
}
