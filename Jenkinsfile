pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/SujanShankar/mintpay-warmup.git'
            }
        }

        stage('Run Script') {
            steps {
                sh 'chmod +x start.sh'
                sh './start.sh'
            }
        }
    }
}
