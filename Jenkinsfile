pipeline {
    agent any
    tools {
        maven 'Maven3.3.9'
        jdk 'JDK1.8'
    }
    stages {
        stage('Build') {
            steps { 
                sh 'mvn -Dmaven.test.failure.ignore=true install'
            }
        }
    }
}