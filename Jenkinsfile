pipeline {
  triggers {
    cron('0 0 * * *')
  }
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
        
        input 'We need some input...ok?'
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
