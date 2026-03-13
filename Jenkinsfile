pipeline {
    agent any

    stages {
        stage('Compile Java Program') {
            steps {
                bat 'javac helloWorld.java'
            }
        }

        stage('Run Java Program') {
            steps {
                bat 'java helloWorld'
            }
        }
    }
}
