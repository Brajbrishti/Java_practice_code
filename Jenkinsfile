pipeline {

    agent any

    tools {
        jdk 'JDK17'
    }
        stage('Checkout Code')
        {
            git branch: 'main',
            url: 'https://github.com/Brajbrishti/Java_practice_code.git'
        }

        stage('Compile') 
        {
            bat 'javac HelloWorld.java'
        }

        stage('Run Program') 
        {
            bat 'java HelloWorld'
    }
}