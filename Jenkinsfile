pipeline {
    agent any

    stages {
        stage('Git') {
            steps {
                echo 'Pulling...'
                git branch: 'main',
                    url: 'https://github.com/nerimene347-png/Devops.git'
            }
        }

        stage('Maven Build') {
            steps {
                sh 'mvn -version'
            }
        }
    }
}
