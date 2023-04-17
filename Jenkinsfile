pipeline {

  agent any
  stages {
 stage('Build') {
      steps {
        sh 'docker build -t lloydmatereke/jenkins-docker-hub .'
      }
    }
    stage('Building image') {
      steps{
     
       sh 'node --version'


          }
      }
   
    
    
  }
}
