pipeline {
    agent any
    tools {
        maven 'apache-maven-3.1.2'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}