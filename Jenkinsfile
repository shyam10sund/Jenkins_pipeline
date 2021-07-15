pipeline {
    agent {
       master
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn clean package' 
            }
        }
    }
}
