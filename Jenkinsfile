pipeline {
  agent any
  stages {
    stage('SOURCE') {
      steps {
        git 'https://github.com/Vinoth8778/SampleProject.git'
      }
    }
    stage('BUILD') {
      steps {
        bat 'mvn clean install'
      }
    }
  }
}