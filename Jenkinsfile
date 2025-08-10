pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Fatima-cloud-ops/lawyerproject2.git'
            }
        }
        stage('Build') {
            steps {
                echo 'No build needed for plain HTML/CSS/JS project'
            }
        }
        stage('Test') {
            steps {
                echo 'No tests configured'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy your site manually or automate here'
            }
        }
    }
}
