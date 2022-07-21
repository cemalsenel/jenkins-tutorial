pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "hello world"
                sh 'echo second step'
                sh 'echo another step'                
                sh '''
                echo 'Multiline'
                echo 'Example'
                '''
                echo 'not using shell'
            }
        }
    }
}