pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                sh 'echo \'hello world\'' 
            }
        }
        stage('Test'){
            steps {
                sh 'echo \'this is a test\''
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo \'this is me deploying\''
            }
        }
    }
}
