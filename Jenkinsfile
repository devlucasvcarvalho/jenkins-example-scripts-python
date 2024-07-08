pipeline {
  agent {
    docker { 
      image 'python:3.12.4-alphine3.20' 
    }
  }
  stages {
    stage('phyton') {
      steps{
        sh 'sudo apt install python3'
      }
    } 
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
}
