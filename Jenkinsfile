pipeline {
    agent any

    stages {
        stage('Compile Java Code') {
            steps {
                sh 'javac Main.java'
            }
        }
        stage('Run Java Program') {
            steps {
                sh 'java Main'
            }
        }
    }
}
