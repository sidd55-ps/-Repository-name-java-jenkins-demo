pipeline {
    agent any

    stages {
        stage('CHECK PROJECT') {
            steps {
                bat 'dir'
            }
        }

        stage('COMPILE') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }

        stage('RUN') {
            steps {
                bat 'java HelloWorld'
            }
        }
    }
}