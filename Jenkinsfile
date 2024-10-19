pipeline {
    agent any
   
    stages {
        stage('Build') {
            steps {
                sh 'mvn compile'
            }
        }
        stage('Package') {
            steps {
                mvn package -DskipTests
            }
        }
    }
}