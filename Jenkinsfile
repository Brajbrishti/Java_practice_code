pipeline {
    agent any

    stages {

        stage('Checkout Code') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Brajbrishti/Java_practice_code.git'
            }
        }

        stage('Compile') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }

        stage('Run Program') {
            steps {
                bat 'java HelloWorld'
            }
        }
    }
}
