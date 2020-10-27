pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
        stage('build script') {
            steps {
            sh 'python main.py'
            }
        }
          stage('install requirements') {
            steps {
                sh 'pip install -r requirements.txt'
            }
     
        }
    }
}
