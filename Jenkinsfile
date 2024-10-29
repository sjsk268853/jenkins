pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python --version' // Replace 'python3' with 'python' if 'python3' is not available on Windows
      }
    }
    stage('hello') {
      steps {
        bat 'python p1.py' // Adjust to 'python' as well
      }
    }
  }
}
