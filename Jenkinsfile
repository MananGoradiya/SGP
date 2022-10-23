/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    tools {
        maven 'maven 3_0_5'
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
