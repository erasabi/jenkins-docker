pipeline {
    agent { 
        dockerfile {
            args "-v /tmp:/tmp -p 80:80/tcp"
        }
    }
    stages {
        stage('Test') {
            steps {
                sh 'ifconfig'
            }
        }
    }
}
