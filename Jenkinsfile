pipeline {
  agent any
  stages {
    stage('Testing') {
      steps {
        echo 'This is a test'
        sh 'echo \'this is a shell script\''
      }
    }
    stage('Build') {
      steps {
        timestamps() {
          sh 'echo \'this is a build\''
        }
        
      }
    }
    stage('Deploy') {
      steps {
        echo 'You have deployed'
        sh 'echo \'this is a deploy\''
      }
    }
  }
}