pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "HELLO Ayo"'
      sh '''
        echo "Welcome to B2"
        uname -a
        '''
      }
    }
    stage ('Test') {
      steps {
      sh 'echo "HELLO Akin"'
      sh '''
        echo "This is testing"
        pwd
        '''
      }
    }
  }
}
