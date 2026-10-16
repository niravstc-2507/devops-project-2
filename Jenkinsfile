
pipeline {
    agent any

    stages {
        stage('Project Information') {
            steps {
                echo 'Project: devops-project-2'
                echo 'Repository: GitHub'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project 2...'
                sh 'pwd'
                sh 'ls -la'
            }
        }
    }

    post {
        success {
            echo 'Project 2 pipeline completed successfully!'
        }
        failure {
            echo 'Project 2 pipeline failed.'
        }
    }
}
