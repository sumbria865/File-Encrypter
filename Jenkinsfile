pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                // Clone your GitHub repo
                git branch: 'main', url: 'https://github.com/sumbria865/File-Encrypter.git'
            }
        }
        stage('Build') {
            steps {
                sh '''
                echo "Building Java project..."
                ls
                mkdir -p build
                javac -d build "Password Protection"/*.java
                echo "Build successful"
                '''
            }
        }
    }
}
