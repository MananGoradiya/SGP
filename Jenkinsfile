/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    tools {
        maven 
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
