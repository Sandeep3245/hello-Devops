pipeline {
    agent any
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