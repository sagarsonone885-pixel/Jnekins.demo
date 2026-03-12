pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                echo "Cloning code from GitHub"
            }
        }

        stage('Check Files') {
            steps {
                bat 'dir'
            }
        }

        stage('Build') {
            steps {
                bat 'echo Build successful'
            }
        }

    }
}
