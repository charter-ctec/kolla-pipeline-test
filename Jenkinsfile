pipeline {
    agent { 
        node { 
            label 'kolla_test' 
        } 
    }
    stages {
        stage('build') {
            steps {
                sh 'cd /root/scripts'
            }
            steps {
                sh 'python getCommit.py'
            }
        }
    }
}
