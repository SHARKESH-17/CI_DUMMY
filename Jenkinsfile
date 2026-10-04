pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/SHARKESH-17/CI_DUMMY.git'
            }
        }

        stage('Build') {
            steps {
                sh 'javac Hello.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Hello'
            }
        }
    }
}
