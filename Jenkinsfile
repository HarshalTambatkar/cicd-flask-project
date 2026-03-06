pipeline {
    agent any

    stages {

        stage('Install Dependencies') {
            steps {
                bat 'python -m pip install -r requirements.txt'
            }
        }

        stage('Build Check') {
            steps {
                bat 'python --version'
                echo 'Pipeline executed successfully'
            }
        }

    }
}
