pipeline {
    agent {
        docker {
            image 'openjdk:17-alpine'  // Use Java 17 in a lightweight Alpine Linux container
        }
    }
    stages {
        stage('Compile Java') {
            steps {
                sh 'javac HelloWorld.java'
            }
        }
        stage('Run Java App') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}

