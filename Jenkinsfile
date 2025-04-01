pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/your-username/jenkins-ci-cd-practice.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building the application..."'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
                sh 'python app.py'  // Run the Python app
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploying application to production..."'
            }
        }
    }
}
