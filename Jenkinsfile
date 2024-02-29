pipeline {
    agent {
        label 'jenkins_slave1'
    } 
    stages {
        stage('Build') { 
            steps {
                echo 'build success'
            }
        }
        stage('Test') { 
            steps {
                echo 'test success'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'Deploy success' 
            }
        }
    }
}