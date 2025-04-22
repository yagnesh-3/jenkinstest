pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                echo "just a simple building stage"
                sh 'cat hello.txt'
            }
        }
        stage('Done'){
            steps{
                echo "Build completed. You can add more later."
            }
        }
    }
}