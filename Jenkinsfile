pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                // In a real project, this would be a build command, e.g., 'mvn clean install'
                sh 'echo "Build complete."'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // This is where you would run your unit and integration tests
                sh 'echo "Tests passed successfully."'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Simulating deployment...'
                sh 'echo "Deployment simulated successfully."'
            }
        }
    }
}
