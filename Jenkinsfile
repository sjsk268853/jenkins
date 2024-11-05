pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python --version' // Checks Python version
      }
    }
    stage('hello') {
      steps {
        bat 'C:\\Users\\hp\\AppData\\Local\\Programs\\Python\\Python311\\python.exe p1.py' // Execute the script directly
      }
    }
  }
}
