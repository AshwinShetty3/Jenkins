pipeline {
    agent any
    
    triggers {
        githubPush()
    }
    
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/AshwinShetty3/Jenkins'
            }
        }
        
        stage('Build') {
            steps {
                echo "Building the code..."
                // Add your build steps here
            }
        }
    }
}
