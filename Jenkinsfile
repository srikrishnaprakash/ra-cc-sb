pipeline {
    agent any
   
    stages {
        stage('Build') {
            steps {
                mvn compile
            }
        }
        stage('Package') {
            steps {
                mvn package -DskipTests
            }
        }
    }
}