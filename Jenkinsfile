pipeline {
    agent any
    tools {
        maven 'maven' // use the name configured in Jenkins
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }
}
