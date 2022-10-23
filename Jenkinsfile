/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    tools {
        maven 'maven_3_5_0'
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
