pipeline {
  agent any
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
