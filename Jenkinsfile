pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Starting Build'
                withMaven {
                    sh "mvn clean compile"
                }
            }
        }
        stage('Tests') {
            steps {
                echo 'Starting tests'
                withMaven {
                    sh "mvn clean compile"
                }
            }
        }
    }
}