pipeline {
    agent any
    
    stages {
        stage('Run Shell Script') {
            steps {
                // We use 'bat' to tell Windows to open Bash, and then pass it the Linux commands!
                bat '"C:\\Program Files\\Git\\bin\\bash.exe" -c "chmod +x hello.sh && ./hello.sh"'
            }
        }
    }
}