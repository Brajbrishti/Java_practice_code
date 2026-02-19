node {
    stage('Checkout Code')
    {
        git branch: 'main',
        url: 'https://github.com/Brajbrishti/Java_practice_code.git'
    }

    stage('Compile') 
    {
        sh 'javac HelloWorld.java'
    }

    stage('Run Program') 
    {
        sh 'java HelloWorld'
    }
}