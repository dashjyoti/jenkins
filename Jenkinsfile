gipeline {
    agent any
    tools {
        maven 'maven' 
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn install dockerfile:push'
            }
        }
    }
}