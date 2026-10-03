pipeline {
    agent any

    stages {
        stage('Checkout GIT') {
            steps {
                echo 'Pulling...'
                git branch: 'main',
                    url: 'https://github.com/TON-COMPTE/jenkins-tp.git'
            }
        }

        stage('Date système') {
            steps {
                sh 'date'
            }
        }
    }
}
