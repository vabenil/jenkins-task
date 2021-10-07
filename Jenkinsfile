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
                echo 'Prepare'
            }
        }
        stage('Test') {
            agent {
                docker {
                    image 'ubuntu:20.04'
                }
            }
            steps {
                echo 'Test'
            }
        }
        stage('Deploy') {
            agent {
                docker {
                    image 'ubuntu:20.04'
                }
            }
            steps {
                echo 'Deploy'
            }
        }
    }
}
