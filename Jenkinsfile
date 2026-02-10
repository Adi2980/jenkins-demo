pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/<your-username>/jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Running build stage..."'
                sh './app.sh'
            }
        }
    }
}
