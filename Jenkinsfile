pipeline {
    agent any
    
    // This is the map! It temporarily tells Windows exactly where Git Bash lives for this run.
    environment {
        PATH = "C:\\Program Files\\Git\\bin;${env.PATH}"
    }
    
    stages {
        stage('Run Shell Script') {
            steps {
                sh 'chmod +x hello.sh && ./hello.sh'
            }
        }
    }
}