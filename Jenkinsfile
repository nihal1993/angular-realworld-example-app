pipeline {
    agent any
    stages {
        stage('Welcome Step') {
            steps { 
                sh 'npm install -g @appthreat/cdxgen'
                sh 'cdxgen -o bom.json'
            }
        }
    }
}
