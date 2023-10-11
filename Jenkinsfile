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
            def gitleaksPath = sh(script: 'which gitleaks', returnStdout: true).trim()
            sh "${gitleaksPath} --path=yourrepository"
        }
    }
}

    }
}
