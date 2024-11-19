pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/Androkal19/TR3-Astra.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add build commands here (e.g., mvn, npm, or pip commands)
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test commands here (e.g., mvn test, npm test, pytest)
            }
        }
    }

    post {
        always {
            echo 'Pipeline execution completed!'
        }
    }
}
