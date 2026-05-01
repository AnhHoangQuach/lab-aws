pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                echo 'Building.......'
                // For example: sh './gradlew build' or 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing......'
                // For example: sh './gradlew test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying.........'
                // For example: sh './deploy.sh'
            }
        }
    }
}
