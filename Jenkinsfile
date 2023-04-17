pipeline {

  agent any
  stages {
 stage('Build') {
      steps {
        app = docker.build("momo979/purple-beard-team-2")
      }
    }
    stage('Building image') {
      steps{
      app.inside {
       sh 'node --version'

      }
          }
      }
   
    
    
  }
}
