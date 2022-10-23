/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    tools {
        maven 'maven 3.5.0'
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
