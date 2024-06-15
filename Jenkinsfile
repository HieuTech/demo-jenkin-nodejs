pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', 
                    url: 'https://github.com/HieuTech/demo-jenkin-pipeline.git'
            }
        }
    }
}