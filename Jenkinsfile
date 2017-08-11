pipeline {
    agent { 
        node { 
            label 'kolla_test' 
        } 
    }
    stages {
        stage('build') {
            steps {
                sh 'docker --version'
            }
        }
    }
}
