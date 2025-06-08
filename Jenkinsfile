pipeline {
    agent any
    tools {
        maven 'MAVEN_HOME' // Make sure this name matches Jenkins Maven config
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }
}
