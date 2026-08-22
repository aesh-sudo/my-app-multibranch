pipeline {
    agent any
    
    stages {
        stage('Hello from main') {
            steps {
                echo 'This is the MAIN branch!'
                echo 'Branch name: main'
                echo "Build number: ${BUILD_NUMBER}"
            }
        }
        
        stage('Simple Test') {
            steps {
                echo 'Running tests...'
                sh 'echo "Tests passed!"'
            }
        }
    }
}
