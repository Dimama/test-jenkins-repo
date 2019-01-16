pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python --version'
		python3 main.py
            }
        }
    }
}
