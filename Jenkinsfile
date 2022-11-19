pipeline {
    agent any
    stages {
        stage('Check') {
            steps {
                sh "ls -la; ip a; cat /etc/hostname"
            }
        }
    }
}
