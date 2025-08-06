pipeline {
  agent any 
  stages {
    stage ('Hello') {
      steps {
        echo "Hello from jenkins"
      }
    }
    stage ('Checking Date') {
      steps {
        sh 'date'
      }
    }
     stage ('listing all the files') {
      steps {
        sh 'ls -la'
      }
    }
    stage ('Make a parent directory') {
      steps {
        sh 'mkdir -p Parent'
      }
    }
  }
}
