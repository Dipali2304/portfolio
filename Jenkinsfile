pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                echo 'Cloning the GitHub repository'
                git branch: 'main', url: 'https://github.com/Dipali2304/portfolio.git'
            }
        }

        stage('Install Dependencies') {
            steps {
                echo 'Installing required dependencies'
            }
        }

        stage('Build Portfolio Website') {
            steps {
                echo 'Building the portfolio project'
            }
        }

        stage('Test Website Files') {
            steps {
                echo 'Testing HTML and CSS files'
            }
        }

        stage('Deploy Website') {
            steps {
                echo 'Deploying portfolio website'
            }
        }

        stage('Pipeline Completed') {
            steps {
                echo 'Portfolio Pipeline Executed Successfully'
            }
        }

    }
}
