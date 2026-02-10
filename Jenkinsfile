pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Adi2980/jenkins-demo.git'
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
