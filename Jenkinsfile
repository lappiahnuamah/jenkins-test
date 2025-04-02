pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/lappiahnuamah/jenkins-test'
            }
        }
        stage('Confirm Clone') {
            steps {
                sh 'ls -la'
            }
        }
    }
}
