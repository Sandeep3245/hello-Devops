pipeline{
    agent any
    stages{
        stage('run shell script'){
            steps{
                sh'''
                chmod +x hello.sh && ./hello.sh
            }
        }
    }

}