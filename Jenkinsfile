pipeline {
    agent {
        label 'Agent-1'
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo this is from build'
            }
        }
        stage('Test') {
            steps {
                sh 'echo this is from Test'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo this is from Deploy'
            }
        }
    }
}