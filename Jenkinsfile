pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Starting Build'
                withMaven (maven: 'maven-3') {
                    sh "mvn clean compile"
                }
            }
        }
        stage('Tests') {
            steps {
                echo 'Starting tests'
                withMaven (maven: 'maven-3'){
                    sh "mvn clean compile"
                }
            }
        }
    }
}