pipeline {

  agent any
  stages {
 stage('Build') {
      steps {
        script {
        app = docker.build("momo979/purple-beard-team-2")
        }
      }
    }
    stage('Building image') {
      steps{
        script {
      app.inside {
       sh 'node --version'

      }
        }
          }
      }
   
    
    
  }
}
