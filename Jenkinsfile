pipeline {
    agent any
  
    tools {nodejs "nodejs"}
  
    stages {
        stage('Welcome Step') {
            steps { 
                sh 'npm install'
                sh 'npm install -g @appthreat/cdxgen'
                sh 'cdxgen -o bom.json'
            }
        }
    }
}
