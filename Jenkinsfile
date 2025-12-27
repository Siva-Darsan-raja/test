pipeline{
    agent any

    stages {
        stage('Test Webhook') {
            steps {
                sh 'chmod +x test.sh'
                sh './test.sh'
            }
        }
    }

}







