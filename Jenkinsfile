/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    tools {
        maven 'maven 3.0.5'
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
