pipeline {
    agent { 
        node { 
            label 'kolla_test' 
        } 
    }
    stages {
        stage('build') {
            steps {
                sh 'python /root/scripts/getCommit.py'
            }
        }
    }
}
