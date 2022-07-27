pipeline {
  agent any
  stages {
    stage('Starting ...') {
      steps {
        echo 'Initialize' 
      }
    }
    stage('Compile') {
      steps {
        sh 'javac Start.java'
        sh 'java Start'
      }
    }
  }
}
