pipeline {
    agent none 
    stages {
        stage('Build') {
            agent {
                docker {
                    image 'busybox' 
                }
            }            
            steps {
                sh 'echo hello'
            }
        }
    }
}
