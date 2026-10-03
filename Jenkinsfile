pipeline {
    agent any

    stages {
        stage('Checkout GIT') {
            steps {
                echo 'Pulling...'
                git branch: 'main',
                    url: 'https://github.com/nerimene347-png/Devops.git'
            }
        }

        stage('Date systeme') {
            steps {
                sh 'date'
            }
        }
    }
}
