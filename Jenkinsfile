pipeline {
    agent any
    
    stages {
        stage('Install Dependencies') {
            steps {
                // Run npm install to install dependencies
                script {
                    sh 'npm install'
                }
            }
        }
        
        stage('Run Tests') {
            steps {
                // Run mocha to execute tests
                script {
                    sh 'mocha'
                }
            }
        }
    }
}
