pipeline {
  agent any
  environment {
    PATH = "$PATH:/opt/apache-maven-3.9.11/bin"
  }
  stages {
    stage('GetCode') {
      steps {
        git branch: 'main',
            url: ''https://https://github.com/MilaDev7/Jenkins-repo.git'
      }
    }
    stage('Build') {
      steps {
        sh 'mvn clean package'
      }
    }
  }
}
