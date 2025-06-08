pipeline {
    agent any
    tools {
        jdk 'jdk21'  // <-- Must match the name you gave in Jenkins
        maven 'maven'  // Already configured
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }
}
