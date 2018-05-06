pipeline {
  agent any
  tools {
  maven 'test1'
  }
  stages {
    stage ('Compile Stage'){
      steps {
            sh 'mvn compile'
            }
      }
      stage ('Package Stage'){
        steps{
              sh 'mvn package'
              }
         }
       }
   }
