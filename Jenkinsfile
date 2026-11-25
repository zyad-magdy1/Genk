pipeline {
    agent any
    stages {
        stage('Compile') {
            steps {
                echo 'Compiling...'
                bat 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                echo 'Running...'
                bat 'java HelloWorld'
            }
        }
    }
}
