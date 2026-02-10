pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    if (isUnix()) {
                        sh 'echo Running build stage...'
                        sh 'echo Hello from Jenkins CI Demo!'
                    } else {
                        bat 'echo Running build stage...'
                        bat 'echo Hello from Jenkins CI Demo!'
                    }
                }
            }
        }
    }
}
