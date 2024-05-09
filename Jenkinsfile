pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Karthik351/NCPLweekendtask.git']])
            }
        }
        stage('Build') {
            steps {
                echo "This is my first Jenkins pipline"
            }
        }
    }
}
