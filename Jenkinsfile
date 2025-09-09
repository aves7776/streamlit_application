pipeline {
  agent any
  
  stages {
    stage('Git repo pull') {
      steps {
        script {
          // creating a directory 
          git 'https://github.com/aves7776/streamlit_application.git'
        }
      }
    }
  }
}
