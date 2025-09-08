pipeline {
  agent any
  
  stages {
    stage('GIT REPO PULL') {
      steps {
        script {
          // creating a directory 
          git 'https://github.com/aves7776/streamlit_application.git'
        }
      }
    }
  }
}
