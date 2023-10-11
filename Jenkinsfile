pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo "Build success"
            }
        }

      stage('Gitleaks') {
    steps {
        script {
            sh '/usr/local/bin --path=yourrepository'
        }
    }
}

    }
}

