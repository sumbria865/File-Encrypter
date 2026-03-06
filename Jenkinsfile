pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/sumbria865/File-Encrypter.git'
            }
        }
        stage('Build') {
            steps {
                sh '''
                echo "Building Java project from src folder..."
                mkdir -p build
                javac -d build "Password Protection/src"/*.java
                echo "Build successful"
                '''
            }
        }
    }
}
