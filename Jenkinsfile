pipeline {
  agent label
    docker { 
      image 'python:3.12.4-alpine3.20' 
    }
  }
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('hello') {
      steps {
        sh 'python3 hello.py'
      }
    }
  }
 
