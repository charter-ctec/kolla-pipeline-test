pipeline {
    agent { 
        node { 
            label 'kolla_test' 
        } 
    }
    stages {
        stage('build') {
            steps {
                sh 'python getCommit.py'
            }
        }
    }
}
