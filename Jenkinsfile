pipeline {
    agent any
    parameters {
        string(name: 'INPUT_TEXT', defaultValue: '', description: 'Some input string')
    }
    stages {
        stage('version') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('hello') {
            steps {
                sh 'python3 src/test_jenkins.py'
            }
        }
    }
}