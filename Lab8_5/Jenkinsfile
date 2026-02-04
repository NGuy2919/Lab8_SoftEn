pipeline {
    agent any

    stages {
        stage('Check Environment') {
            steps {
                sh 'python3 --version'
                sh 'robot --version'
            }
        }

        stage('Run Robot Tests') {
            steps {
                sh 'robot tests/Lab8.robot'
            }
        }
    }
}
