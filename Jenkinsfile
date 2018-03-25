pipeline {
  agent any
  stages {
    stage('SOURCE') {
      steps {
        git 'https://github.com/Vinoth8778/'
      }
    }
    stage('BUILD') {
      steps {
        bat 'mvn clean install'
      }
    }
  }
}