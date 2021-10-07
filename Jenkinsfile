pipeline {
    agent none
    stages {
        stage('Prepare') {
            agent {
                docker {
                    image 'ubuntu:20.04'
                }
            }
            steps {
                sh 'echo Prepare'
            }
        }
        stage('Test') {
            agent {
                docker {
                    image 'ubuntu:20.04'
                }
            }
            steps {
                sh 'echo Test'
            }
        }
        stage('Deploy') {
            agent {
                docker {
                    image 'ubuntu:20.04'
                }
            }
            steps {
                sh 'Echo Deploy'
            }
        }
    }
}
