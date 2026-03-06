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
