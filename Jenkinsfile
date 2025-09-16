pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                bat 'python --version'
            }
        }

        stage('hello') {
            steps {
                bat 'python demo.py %x_value% %y_value%'
            }
        }
    }
}