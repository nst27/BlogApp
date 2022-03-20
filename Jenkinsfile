pipeline{
  agent any
  tools {nodejs "node"}
  
  stages{
    stage("Hello"){
      steps{
        sh "npm install"
      }
    }
    stage('Deploy'){
      steps{
        sh "node app.js"
      }
    }
  }

}
