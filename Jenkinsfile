stage ('Generating Software Bill of Materials') {
    steps {
        //Building the dependencies to generate SBoM
        sh 'npm install -g @appthreat/cdxgen'
        sh 'cdxgen -o bom.json'
    }
}
