pipeline {
  agent any
  tools {
    maven 'Maven3'
  }
  stages{
    stage("Maven Build"){
      steps{
        sh "mvn clean package"
      }
    }
  }
}
